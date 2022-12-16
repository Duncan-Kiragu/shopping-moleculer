[![Moleculer](https://badgen.net/badge/Powered%20by/Moleculer/0e83cd)](https://moleculer.services)

# shopping-moleculer
This is a [Moleculer](https://moleculer.services/)-based microservices project. Generated with the [Moleculer CLI](https://moleculer.services/docs/0.14/moleculer-cli.html).

## Usage
Start the project with `npm run dev` command. 
After starting, open the http://localhost:3000/ URL in your browser. 
On the welcome page you can test the generated services via API Gateway and check the nodes & services.

In the terminal, try the following commands:
- `nodes` - List all connected nodes.
- `actions` - List all registered service actions.
- `call greeter.hello` - Call the `greeter.hello` action.
- `call greeter.welcome --name John` - Call the `greeter.welcome` action with the `name` parameter.
- `call products.list` - List the products (call the `products.list` action).


## Services
- **api**: API Gateway services
- **greeter**: Sample service with `hello` and `welcome` actions.
- **products**: Sample DB service. To use with MongoDB, set `MONGO_URI` environment variables and install MongoDB adapter with `npm i moleculer-db-adapter-mongo`.

## Mixins
- **db.mixin**: Database access mixin for services. Based on [moleculer-db](https://github.com/moleculerjs/moleculer-db#readme)


## Useful links

* Moleculer website: https://moleculer.services/
* Moleculer Documentation: https://moleculer.services/docs/0.14/

## NPM scripts

- `npm run dev`: Start development mode (load all services locally with hot-reload & REPL)
- `npm run start`: Start production mode (set `SERVICES` env variable to load certain services)
- `npm run cli`: Start a CLI and connect to production. Don't forget to set production namespace with `--ns` argument in script
- `npm run lint`: Run ESLint
- `npm run ci`: Run continuous test mode with watching
- `npm test`: Run tests & generate coverage report
- `npm run dc:up`: Start the stack with Docker Compose
- `npm run dc:down`: Stop the stack with Docker Compose
# shopping-moleculer

## User Stories

- As a customer, I want to be able to browse the store's catalog and view product details, so that I can find the products I'm interested in.
- As a customer, I want to be able to add items to my shopping cart and modify the quantities of items in my cart, so that I can easily keep track of the items I want to purchase.
- As a customer, I want to be able to check out and complete my purchase quickly and easily, so that I can get my items as soon as possible.
- As a customer, I want to be able to view the status of my orders and receive notifications when my orders are shipped, so that I can stay informed about the progress of my purchases.
- As a customer, I want to be able to contact customer service for support or to report issues with my orders, so that I can get help if I need it.
- As a store administrator, I want to be able to manage products, categories, and promotions, so that I can keep the store up to date and promote my products effectively.
- As a store administrator, I want to be able to view analytics and reporting data, so that I can understand my customers' behavior and improve the store's marketing and sales efforts.
- As a customer, I want to be able to search for products using keywords or categories, so that I can easily find the items I'm looking for.
- As a customer, I want to receive personalized product recommendations based on my past purchases and browsing history, so that I can discover new products that I might be interested in.
- As a customer, I want to be able to shop on the go using the store's mobile app, so that I can shop anytime, anywhere.
- 
- 
- As a store administrator, I want to be able to integrate with external shipping providers to fulfill orders, so that I can offer a variety of shipping options to my customers.
- As a store administrator, I want to be able to set up multiple payment gateways to support different payment methods, so that I can accommodate my customers' preferred payment options.
- As a customer, I want to be able to save items to a wishlist for future purchase, so that I can keep track of products I'm interested in but not ready to buy yet.
- As a customer, I want to be able to compare products side by side before making a purchase, so that I can make informed decisions about which product to buy.
- As a store administrator, I want to be able to set up abandoned cart reminders to encourage customers to complete their purchases, so that I can maximize sales and revenue.
- As a customer, I want to be able to leave reviews and ratings for products I have purchased, so that I can share my thoughts and help other customers make informed decisions.
- As a store administrator, I want to be able to respond to customer reviews and ratings, so that I can address any issues or concerns and improve the store's reputation.
- As a customer, I want to be able to subscribe to newsletters and marketing emails to receive updates and promotions from the store, so that I can stay informed about new products and special offers.
- As a store administrator, I want to be able to send targeted marketing emails to specific customer segments based on their past purchases and interests, so that I can more effectively promote my products to relevant customers.
- 
- 
- 
- As a customer, I want to be able to create an account and log in to access my order history and personal information, so that I can easily track my purchases and update my account details.
- As a store administrator, I want to be able to manage customer accounts and data, so that I can keep track of my customers and provide personalized experiences.
- As a customer, I want to be able to securely store my payment information for faster checkout in the future, so that I don't have to enter my payment details every time I make a purchase.
- As a store administrator, I want to be able to process returns and exchanges for customers, so that I can provide a smooth and satisfactory shopping experience.
- As a customer, I want to be able to easily navigate the store and find what I'm looking for, so that I can shop efficiently and effectively.
- As a store administrator, I want to be able to customize the appearance and branding of the store, so that I can create a unique and visually appealing shopping experience for my customers.
- 