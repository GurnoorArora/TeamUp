

<h1><img src="https://user-images.githubusercontent.com/59141533/131732817-23a34498-10d3-4024-9519-d064a67a8482.png" width=50px height=50px />Team Maker</h1> 

# The problem Team Maker solves

A real-world issue we've encountered while looking for a team to participate in a hackathon is finding a random teammate or team and synchronising our abilities as best we can, which is extremely difficult to do with people we don't know anything about. Team Maker attempts to address this issue by allowing users to search for teams using multiple filters and learn about one another via user portfolios.



<!-- ## Screenshots

![App Screenshot](https://res.cloudinary.com/dcgefz04y/image/upload/v1624793593/Screenshot_275_oibipb.png) -->

  
# Features

- User and Admin Authentication.
- Creation of Teams.
- Searching for Teams.
- Colloboration with Teams( Chat functionality ).
- List of all events like hackathons, competitions(for now we only support few events).
- Custom addition of events by Admin.
- Team and User Profiles.


  
## Tech Stack

**Client:** React Js, Redux, Material UI

**Server:** Node Js ( Express Js )

**Database:** MongoDB

**Others:** Socket.io, AWS S3



  
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file in root directory.

`MONGO_URI`

`JWT_SECRET`

  
## Run Locally

Clone the project

```bash
git clone https://github.com/veerreshr/team-maker.git
```

Go to the project directory

```bash
cd team-maker
```

Install dependencies

```bash
npm install
```
Go to the fronend directory
```bash
cd frontend
```

Install dependencies

```bash
npm install
```
Go to the root directory
```bash
cd ..
```

Start the server

```bash
npm run dev
```
  
Also refer [Contributing-gitflow](https://github.com/veerreshr/team-maker/blob/main/CONTRIBUTING-gitflow.md) for more information 
## Roadmap

- [ ] Add ESLint
- [x] Landing Page
- [x] User Profile
- [x] Event Section
- [x] Team Filtering
- [x] Chat Implementation
- [ ] Dockerize the application
- [ ] Implement Testing 
- [ ] Voice/Video call Implementation(Optional)
- [ ] Kanban Boards( optional )  

## Support

For support, Please email us at veerreshr@gmail.com

## License

[MIT](https://choosealicense.com/licenses/mit/)

  
