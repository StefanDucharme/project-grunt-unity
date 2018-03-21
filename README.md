# project-grunt-unity

## Unity Notes:
- Rigidbody2d + colider = dynamic object. Good for performance if they move (ex. pickup that rotates) since unity will not recalculate the collider for the static objects. If it was static (ex. just had collider) it would recalc all static objects (not sure if all or just for the prefab)
