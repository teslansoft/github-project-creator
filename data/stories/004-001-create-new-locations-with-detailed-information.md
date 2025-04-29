---
label: Location Management
role: traveler
action: create new locations with detailed information
benefit: I can document places I've visited or plan to visit
---

![wireframe](https://i.imgur.com/ipXW3tg.png)

- [ ] Form accepts name, description, and coordinates
- [ ] Name and description are validated to have a max length
- [ ] Coordinates are validated to be within valid ranges
- [ ] All required fields are validated before submission
- [ ] Confirmation dialog shows when leaving with unsaved changes
- [ ] Add location button shows plus icon
- [ ] Loading spinner displays during creation
- [ ] Back-end responds with 401 when submitting if user is not logged in
- [ ] Submitted data is validated in the back-end
- [ ] Form displays errors returned by back-end
- [ ] Data is inserted into db with a url friendly slug
- [ ] Data is inserted into db with the current users id
- [ ] User is redirected back to dashboard after successful creation
- [ ] App is protected from csrf attacks
