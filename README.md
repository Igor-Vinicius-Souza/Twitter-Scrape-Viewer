# Tweet Viewer

Tweet Viewer is a simple web-based application that allows users to upload a JSON file containing tweet data and display it in a readable and visually appealing format.

## Features

- **User-friendly Interface**: Displays tweets with a clean design, rounded corners, and smooth hover effects.
- **Image Support**: Displays images associated with tweets.
- **Dynamic Loading**: Allows users to upload a JSON file and instantly view the tweet content without hardcoding the data.
- **Responsive Design**: Automatically adjusts to various screen sizes.

## How to Use

1. **Download or Clone the Repository**:  
   - Download the ZIP file or clone the repository:
   ```bash
   git clone https://github.com/your-username/tweet-viewer.git
   ```

2.    **Open ```index.html``` in a Web Browser**:
- Double-click on the ```index.html``` file or open it using your preferred web browser (such as Chrome, Firefox, or Edge).


3.    **Upload a JSON File**:
- Click on the "Choose File" button.
- Select a JSON file containing tweets. The file should follow the format below:

```bash
    json

    {
        "tweets": [
            {
                "link": "https://twitter.com/example/status/123456789",
                "text": "This is an example tweet!",
                "user": {
                    "name": "Example User",
                    "username": "@exampleuser",
                    "profile_id": "1234567890",
                    "avatar": "https://example.com/avatar.jpg"
                },
                "date": "Aug 30, 2024 · 8:28 PM UTC",
                "is-retweet": false,
                "is-pinned": false,
                "external-link": "",
                "replying-to": [],
                "quoted-post": {},
                "stats": {
                    "comments": 10,
                    "retweets": 20,
                    "quotes": 5,
                    "likes": 100
                },
                "pictures": [
                    "https://example.com/image.jpg"
                ],
                "videos": [],
                "gifs": []
            }
        ]
    }
```
<br></br>
- **(You can get those JSON files using the python [ntscraper](https://github.com/bocchilorenzo/ntscraper) library and [Nitter](https://github.com/zedeus/nitter))**
<br></br>
4.    **View the Tweets**:
- The tweets will be displayed on the page with their associated details (like text, user info, stats, and images).

## Project Structure

- **index.html**: The main HTML file containing the structure and JavaScript for loading and displaying tweets.
- **README.md**: Documentation for the project.

## Dependencies

- This project does not require any external dependencies or libraries. It is built with pure HTML, CSS, and JavaScript.

## Contributing

If you have suggestions for improvement or new features, feel free to submit a pull request or open an issue.

1.  Fork the project.
2.  Create your feature branch (```git checkout -b feature/new-feature```).
3.  Commit your changes (```git commit -m 'Add new feature'```).
4.  Push to the branch (```git push origin feature/new-feature```).
5.  Open a pull request.

## License

This project is open source and available under the [MIT License](/LICENSE).

## Contact

For any questions or feedback, please contact igor.vinicius.souza@outlook.com.