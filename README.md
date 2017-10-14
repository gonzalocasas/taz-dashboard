[Embedded](https://github.com/berkutta/lora_happy_buttons_embedded/) | [Backend/Data collection](https://github.com/gonzalocasas/taz-data-collector/) | **Frontend/Dashboard** 

# Feedback Buttons: Dashboard

> Simple web dashboard to visualize the current status of feedback button devices.

Web dashboard based on [Nuxt.js](https://nuxtjs.org/) to visualize the status of feedback buttons devices. It retrieves the data from [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) as structured by the [data collector service](https://github.com/gonzalocasas/taz-data-collector).

For detailed explanation on how the Nuxt.js framework works, checkout the [docs](https://github.com/nuxt/nuxt.js).

## Getting Started

### Prerequisites

Make sure you have [Node.js 8.x+](https://nodejs.org/en/) installed on your system.

### Installation

Open your terminal, go to the project's folder and run:

    npm install

### Usage

To start the development server on localhost:3000 with hot reload:

    npm run dev

To build for production and launch the server:

    npm run build
    npm start

Or to generate the static version of the website:

    npm run generate


## License

This project is licensed under the MIT License, see the [LICENSE](LICENSE) file for details.

## Contributing

1. Fork it (<https://github.com/gonzalocasas/taz-dashboard>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request :D

## Credits

Based on the embedded implementation of [feedback buttons](https://github.com/berkutta/lora_happy_buttons_embedded/) by  [@berkutta](https://github.com/berkutta/) of [kilobyte.ch](https://kilobyte.ch/).
