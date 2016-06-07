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

### Audition Videos

These will have:

- `id`
- `video_link`
- `actor_id`

### Experiences

These will have:

- `id`
- `title`
- `description`

### ActorCastings

These will have:

- `id`
- `actor_id`
- `experience_id`

### Rehearsals

These will have:
- `id`
- `experience_id`

### Rehearsal Reports

These will have:
- `id`
- `rehearsal_id`
- `author_id`

### Photos

Photos will be joined to shows via `PhotoExperienceTaggings`. These will have:
- `id`
- `photo_id`
- `experience_id`

Photos will be joined to users via `PhotoUserTaggings`. These will have:
- `id`
- `photo_id`
- `experience_id`
