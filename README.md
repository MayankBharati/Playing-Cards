# Welcome to Playing-Cards: Your Knowledge Exchange Platform

Playing-Cards is your go-to web-based destination for all things question and answer. Our platform empowers users to curate a wealth of knowledge by posting questions across a myriad of topics, while fellow users provide insightful answers. Every Playing-Cards user enjoys the privilege of initiating thought-provoking queries, and when crafting a new question, they have the flexibility to enrich it with descriptive tags, making it effortlessly discoverable by others.

## Under the Hood

Our ingenious platform is powered by the MERN stack, a cutting-edge technology ensemble. The frontend is an exquisite blend of React JS, Material UI, Redux, and Axios, ensuring a sleek and intuitive user experience. On the backend, we've harnessed the formidable capabilities of Node JS and Express, with the data residing securely in MongoDB. To guarantee seamless deployment and scalability, we've containerized the application with Docker, and it's effortlessly accessible via Heroku.

## The Tech That Drives Us

- **Frontend**: React JS, Material UI, Redux, Redux-thunk, Axios
- **Backend**: Node JS, Express, Mongoose
- **Tools**: Docker, Kubernetes, Heroku CLI
- **Database**: MongoDB
- **Testing**: Jest, Super Tests

## Features That Define Us

At Playing-Cards, we're all about delivering a top-notch user experience:

- **User Registration**: Join our community by signing up through a user-friendly form or using your Google credentials.
- **Engagement**: Once you're in, you can interact with posts by liking, sharing, and adding comments.
- **Ask Anything**: Don't hesitate to ask and share your inquiries with the community.
- **Tagging Made Easy**: Enhance the discoverability of your questions by attaching relevant tags.

## Installation Made Simple

Whether you're a Docker enthusiast or prefer a traditional setup, we've got you covered:

**Docker Installation**:
If you have Docker on your computer, navigate to the root folder and launch the entire application with a simple command:

```bash
docker compose up
```

You'll be able to monitor the application's progress through the terminal.

**Manual Installation**:
If you're not a Docker aficionado, follow these steps:

1. Begin by cloning the repository:
```bash
git clone https://github.com/{username}/PlyCard.git
cd PlyCard
```

2. Install dependencies and fire up the client and server:
```bash
cd client
npm install
npm start
```

```bash
cd server
npm install
nodemon index.js
```

3. Configuration Time:
Create a `.env` file within the server directory and add the following essential variables:

```env
MONGO_URI=<your-mongodb-uri>
SECRET=<your-secret>
```

## A Visual Feast

Here are some snapshots to give you a taste of PlyCard:

![Screenshot 1](https://user-images.githubusercontent.com/67458417/144472227-454f2b16-db07-41f5-a0e4-dc742162e822.png)

![Screenshot 2](https://user-images.githubusercontent.com/67458417/144472321-4796ae4d-9a77-4043-b72d-b22647cdbbc6.png)

## Contribute to Excellence

We welcome contributions from the community. To get involved, simply create a new branch and submit a pull request with your enhancements. Please ensure your changes adhere to our coding standards and are rigorously tested.

## License

PlyCard operates under the MIT License, ensuring that our collaborative knowledge-sharing platform remains open and accessible to all.
