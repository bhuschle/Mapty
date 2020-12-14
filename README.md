# Mapty
Jonas's Class on Local Storage and APIs - Educational Showing
 
Page can be viewed at https://bhuschle.github.io/Mapty/

## Future [not part of the course]
- [ ] Ability to **edit** a workout
- [ ] Ability to **delete** a workout
- [ ] Ability to **delete all** workouts
- [ ] Ability to **sort** workouts by a certain field 
  - e.g. distance
- [ ] **Re-build** Running and Cycling objects coming from local storage
- [ ] More realistic error and confirmation **messages**
- [ ] Ability to position the map to **show all workouts** [very hard]
  - Check leaflet API documentation
- [ ] Ability to **draw lines and shapes** instead of just points [very hard]
- [ ] **Geocode location** from coordinates [only after asynchromous JavaScript section]
  - e.g. "Run in Faro, Portugal"
- [ ] **Display weather** data for workout time and place [only after asynchromous JavaScript section]

## Notes
### **edit**, **delete**
Add button to marker description for each **edit** and **delete**\
addEventListener() to each that completes task\
- remove marker
- remove from workoutContainer
- remove from localStorage

### **delete all**
Add button to the bottom of workoutContainer or next to logo on top of workoutContainer\
addEventListener() to button that completes task\
- remove all from local storage
  - function already in app API under reset()

---
permalink : /index.html
---
