# Quiz example code
This is a example for a simple quiz 
## How to run
1. Clone the repository
2. Run `npm install`
3. Run `npm start`
4. Open your browser and go to `http://localhost:3000`
## How to edit questions
1. Open the file `questions.json`
2. Edit the questions in the questions array with the following format:
```json 
{"question": "(question)", "answer": ["(first correct answer)", "(you can add more by adding more strings in the array)"], "image": "(image url, change this to null if you don't want an image)", "score_share_webhook": "(A discord webhook url, change this to null if you don't want to share the score)"}
```
3. Save the file
4. No need to restart the server, the questions will be reloaded automatically
## How to contribute
1. Fork the repository
2. Make your changes
3. Make a pull request
## How to build the project
1. Run `npm run build`
2. The build will be in the `dist` folder
## Credits
Here are all the packages used in this project:
- [Vite](https://vitejs.dev/)

And here are all the people who contributed to this project:
- nobody yet
## Distribution
You can freely distribute this project, but please give credit to the original author and do not claim it is yours.
## License
This project is licensed under CC0 1.0, you can read the license [here](https://creativecommons.org/publicdomain/zero/1.0/) or in the `LICENSE.md` file.