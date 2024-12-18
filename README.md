# Social Network API

## Description

This is a social network API built using Node.js, Express, and MongoDB. It allows users to create an account, post thoughts, and react to other users' thoughts. Users can also add and remove friends.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Repo](#repo)
- [Video](#video)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/social-network-api.git
    ```
2. Navigate to the project directory:
    ```sh
    cd social-network-api
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    npm run start
    ```
2. For development, you can use:
    ```sh
    npm run dev
    ```
3. The server will be running on `http://localhost:3001`.

## API Routes

### Users

- `GET /api/users` - Get all users
- `GET /api/users/:userId` - Get a single user by ID
- `POST /api/users` - Create a new user
- `PUT /api/users/:userId` - Update a user by ID
- `DELETE /api/users/:userId` - Delete a user by ID
- `POST /api/users/:userId/friends/:friendId` - Add a friend to a user's friend list
- `DELETE /api/users/:userId/friends/:friendId` - Remove a friend from a user's friend list

### Thoughts

- `GET /api/thoughts` - Get all thoughts
- `GET /api/thoughts/:thoughtId` - Get a single thought by ID
- `POST /api/thoughts` - Create a new thought
- `PUT /api/thoughts/:thoughtId` - Update a thought by ID
- `DELETE /api/thoughts/:thoughtId` - Delete a thought by ID
- `POST /api/thoughts/:thoughtId/reaction` - Add a reaction to a thought
- `DELETE /api/thoughts/:thoughtId/reaction/:reactionId` - Remove a reaction from a thought

### Reactions

- `POST /api/thoughts/:thoughtId/reaction` - Create a reaction
- `DELETE /api/thoughts/:thoughtId/reaction/:reactionsId` - DELETE a reaction

### Friends

- `POST /api/users/:userId` - Create a friend
- `DELETE /api/users/:userId` - DELETE a friend

## **Repo:**

[Github Repo](https://github.com/jjfcode/challenge-18-Social-Network-API)

## **Video:**

[Video](https://drive.google.com/file/d/1y_pQPGH9hHYW7H2FG3dWiRpkHUoP6SSJ/view?usp=sharing)



## License

This project is licensed under the MIT License. See the [LICENSE](http://_vscodecontentref_/1) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Questions

If you have any questions, please open an issue or contact me directly at [johnferlito73@gmail.com].