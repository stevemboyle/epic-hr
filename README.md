# Epic HR

A portal through which Epic Immersive can:
- Conduct Auditions
- Schedule Rehearsals
- Share Rehearsal Reports

### Users

This application will have `users`. Those `users` will have:
- `id`
- `username`
- `first_name`
- `last_name`
- `password_digest`
- `bio`
- `headshot`


### Photos

Photos will be joined to shows via `PhotoExperienceTaggings`. These will have:
- `id`
- `photo_id`
- `experience_id`

Photos will be joined to users via `PhotoUserTaggings`. These will have:
- `id`
- `photo_id`
- `experience_id`
