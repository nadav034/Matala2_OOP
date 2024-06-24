# Social Network

## Background
This project implements a social network where users can interact by uploading posts, commenting, liking others' posts, and following each other. The design emphasizes correct planning and implementation of object-oriented design patterns.

## Features
- **User Registration and Authentication**: Users can register with a username and password, log in, and log out.
- **Post Management**: Users can create text posts, image posts, and sale posts.
- **Interactions**: Users can like, comment, and follow/unfollow other users.
- **Notifications**: Users receive notifications for likes, comments, and new posts from followed users.

## Design Patterns
The project utilizes several design patterns:
- **Singleton**: Ensures only one instance of the network exists.
- **Observer**: Manages notifications for user interactions.
- **Factory**: Handles the creation of different post types.

## Getting Started

### Prerequisites
- **Python 3.x**: Ensure you have Python installed. You can download it [here](https://www.python.org/downloads/).

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/social-network.git
    cd social-network
    ```
2. Install required packages (if any):
    ```bash
    pip install -r requirements.txt
    ```
### Running the Project
To run the simulation of the social network:
```bash
python py.main


#Code structure

.
├── src
│   ├── network.py           # Contains the Network class
│   ├── user.py              # Contains the User class
│   ├── post.py              # Contains the Post base class and subclasses
│   └── ...
├── tests
│   └── test_script.py       # Self-testing script
├── docs
│   └── design_patterns.md   # Documentation on design patterns used
├── py.main                  # Entry point of the simulation
├── txt.output               # Expected output for verification
└── README.md                # This file
