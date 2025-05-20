---
label: Event Management
role: site admin
action: create new events with detailed information
benefit: I can publish upcoming community events for users to view and attend
---

- [ ] Form accepts event title, description, date/time, location, category, image, venue, price, and status (draft/published)
- [ ] Title and description have max length validation
- [ ] Price field required for paid events
- [ ] Start and end time must be valid and in the future
- [ ] Required fields are validated before submission
- [ ] Confirmation dialog appears when leaving with unsaved changes
- [ ] Add Event button shows plus icon
- [ ] Loading spinner shows during submission
- [ ] Back-end returns 401 if user is not authenticated
- [ ] Submitted data is validated server-side
- [ ] Form shows error messages returned by the back-end
- [ ] Event is saved with URL-friendly slug and admin’s user ID
- [ ] Redirect to event dashboard after successful creation
- [ ] App is protected from CSRF attacks
