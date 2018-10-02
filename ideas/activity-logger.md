### @Early

- Trigger all events documented in `EventTypes` and send to activity log service
- Add filter by ID to User Search on BackOffice
- Add filter by Email to User Search on BackOffice
- Add filter by Full Name to User Search on BackOffice

### @Ivo

- Talent Advocate / Change application status from BackOffice
- Any Employee / with a Google Account (@mindsky.com) is able to Sign Up with Google Account / Login to BackOffice with Google Account
- Employer / Create Job
- Employer / Login to Employer Dashboard / to Add a Job

### @Selimira

- Create report of Job Seeker metrics for totals for:
  - SignUp
  - Account.Email.Verified
  - Profile Completed
  - Applied to Job

### @Johns

- Style UI of User Search in BackOffice
- Show all applications submited by a Job Seeker
- Define flow and screens that will be needed for Employer Dashboard v1.0.0
- Customise Sign Up Transactional emails being sent from Auth0

#### @Courtney

- Pull reports for number of Job Seekers that were hired
- Search Companies by Job Type posted

@Purity

- `[BUG]` Job Seeker / on Add Experience, show error message if user tries to add without Accomplishment


---

- `Owner ID|User ID == Job Seeker ID`
- `Actor ID == Job Seeker ID`

# `Employer-123 (MindSky)`, `job.applied` WITH `Application-20` BY `selimira` ON `5th September 2017`



# Activity Log

*A specified pursuit in which a user partakes.*

| User/Actor/Who | Action/Event/Happened | Object/Property/What | Owner/Whom | When               | EventMetaData (Reference)       |
| -------------- | --------------------- | :------------------- | ---------- | ------------------ | ------------------------------- |
| Selimira       | Applied               | Job-123              | MindSky    | Date               | `{application_id: 456}`         |
| Early          | Logged In             | N/A                  | N/A        | 5th Sept 2017      | N/A                             |
| Juma           | Application.Declined  | Application-456      | Selimira   | 6th Sept 2017      | N/A                             |
| Ivo            | Reacts                | Photo-Shark-1        | Johns      | 7th Sept 2017      | `{"reaction: 🎃}`               |
| Early          | Like                  | Video-Cat            | Selimira   | 7th Sept 2017      | N/A                             |
| Early          | Purchase              | Book-123             | Penguin    | 8th Sept 2017      | `{order_id: 12, total: "$43"}`  |
| Joanna         | SgnUp.JobSeeker       | N/A                  | N/A        | 8th Sept 2017      | `{email: "joanna@pksh.co"}`     |
| Eleken         | Commented             | 1785604-News-Feed    | jb         | almost 3 years ago | `{id: 403146, comment: "Nice"}` |
| Nelly          | Account.Created       | N/A                  | N/A        | 9th Sept 2017      | `{email: "nelly@gmail.com"}`    |



- `Whom`'s `What`, `Happened` BY `Who` ON `When` — Result `...`
- `Who` `Happened` `Whom`'s `What` (on `When`) — Result `...`
- `Selimira`'s `Application-456`, `Application.Declined` BY `Juma` ON `6th Sept 2017` — Result `...`
- `Selimira`'s `Application-456`, `Application.Declined` BY `Juma` ON `6th Sept 2017` — REF `N/A`
- `MindSky`s `Job-123`, `Applied` BY `Selimira` ON `Date` — Result `{application_id: 456}`


---

`Who` `Happened` `Whom`'s `What` (on `When`) — Result `...`

- Behaviour
- Activtiy
- Events
- Happening
- Humans
- Simple
- Story
- Gossip



Actor, Action, Property..

- Movie
- Activity
- Sales
- Technical
- Cinema
- Market



Event, User

- Activtiy
- Actions
- Tracking
- Data
- Generic
- Technical
- Standard

---

### Define your Events

| Object (required) | Property (optional)  | Event (required)        |
| ----------------- | -------------------- | ----------------------- |
| account           |                      | login                   |
| account           | job_seeker, employer | signup                  |
| account           | email                | verified                |
| profile           |                      | completed               |
| profile           | background           | updated                 |
| profile           | experience           | added, updated, deleted |
| profile           | education            | added, updated, deleted |
|                   |                      |                         |
|                   |                      |                         |

