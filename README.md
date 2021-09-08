# assignment2-Addunoor
# Siddhartha Reddy Addunoor
## Favourite place Hyderabad
Hyderabad is the capital and largest city of the South Indian state of **Telangana**. It was ruled by the **Qutub Shahis, Mughals and the Nizams** which shaped its history. The city is noted for its monuments which includes the masterpiece of **Charminar and the fort of Golconda**.

---

## Maryville to Hollywood.
    1. Directions for Hollywood.
        1. start in Maryville (Missouri) drive for about 2.5 hours
        2. Lincoln (Nebraska).
        3. Lincoln to  North Platte.
        4. North Platte to Capitol Reef National Park.
        5. National Park to Las Vegas.
    2. Finally Hollywood.

 ### Products to be packed for enjoyment.
    - Comfortable Shoes.
    - Weather Appropriate, Layered Attire.
    - Light Jacket.
    - Purse/Backpack.
    - Camera.
    - Extra Batteries/Charger.
    - Refillable Water Bottle.
    - Extra Cash.

---

[Aboutme](AboutMe.md)

---
# Food Table

This table shows location and Amount of Foods.

| *Food*                | *Location*      | *Amount*         |
| ----------------------- | ----------------- | ------------------ |
| Pizza                   | Chennai           | 300 INR            |
| Chicken burger          | Missouri          | 3.49 $             |
| Pani puri               | Delhi             | 40 INR             |
| Biryani                 | Hyderabad         | 200 INR            |

---

## Pithy Quotes

As Osho and Eddie Mumford said:

>Nobody reaches anywhere by believing.

>Money is a tool, so I don't have to be.

---
## Code Fencing

Area of triangle from **Geometry  Elementary/Polygons**

>The area formula is derived by taking each edge AB, and calculating the area of triangle ABO with a vertex at the origin O, by taking the cross-product (which gives the area of a parallelogram) and dividing by 2.
>As one wraps around the polygon, these triangles with positive and negative area will overlap, and the areas between the origin and the polygon will be cancelled out and sum to 0, while only the area inside the reference triangle remains.
>This is why the formula is called the surveyor's formula, since the "surveyor" is at the origin; if going counterclockwise, positive area is added when going from left to right and negative area is added when going from right to left, from the perspective of the origin.

Geometry  Elementary/Polygons [Refernce_link](https://en.wikipedia.org/wiki/Shoelace_formula)

code for Geometry  Elementary/Polygons

```
int signed_area_parallelogram(point2d p1, point2d p2, point2d p3) {
    return cross(p2 - p1, p3 - p2);
}

double triangle_area(point2d p1, point2d p2, point2d p3) {
    return abs(signed_area_parallelogram(p1, p2, p3)) / 2.0;
}

bool clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) < 0;
}

bool counter_clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) > 0;
}
```

Geometry  Elementary/Polygons [Code_link](https://en.wikipedia.org/wiki/Shoelace_formula)












