# OpenAI Image Generator

We can get the Documentation on [Github repository for OpenAI][1]

## Project setup and run

- For production, open the terminal and run `npm run start`
- For development, you can use `npm run dev`

## Backend

- Obtain API Key for OpenAI and complete `.env` file
- Configure the routes at `openaiRoutes.js` and the controller at `openaiController.js`

## Frontend

### HTML

HTML code consists basically of one main block for the image description and size to be entered and a secondary section in which we'll see the AI generated image coming from `OpenAI`.

Also we added a navbar just for easy access to the Documentation.

### Styles

As it was not the focus for this project, we proceed as follows:

- Reused a CSS template
- Obtained spinner from [Codepen][2]

## Credits

Credits to [Traversy Media][3] for creating this project and allowing me to learn by doing.

[1]: https://github.com/openai/openai-node
[2]: https://codepen.io/tbrownvisuals/pen/edGYvx
[3]: https://www.youtube.com/@TraversyMedia
