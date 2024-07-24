# my-youtube-clone

It is a React app based on the functionalities of Youtube.

# installed tailwind

    > npm install -D tailwindcss postcss
    > npx tailwindcss init

    > Created .postcssrc file added below code :
        {
            "plugins": {
                "tailwindcss":{}
            }
        }
    > Inside tailwind.config.js added :
        module.exports = {
            content: ["./src/**/*.{html,js}",]
            theme: {
                    extend:{},
                    },
            plugins: [],
        }
    > Add Tailwind directives in index.css file:
        @tailwind base;
        @tailwind components;
        @tailwind utilities;
