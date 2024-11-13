## The challenge

Your challenge is to build out this product list project that includes a functional cart and get it looking as close to the design as possible.

To get started:
1. Fork this repository
2. Navigate to the `challenge` folder
3. Begin working on your implementation
4. When complete, submit your work via pull request


Technical Requirements:
- Next.js with Server-Side Rendering (SSR) implementation
- Pure CSS only (no frameworks like Tailwind or Bootstrap)
- Preprocessors such as SCSS, SASS, or LESS are permitted

The product data is provided in a `data.json` file. You'll need to implement an API endpoint to fetch and serve this data to your application.

Your users should be able to:

- Add items to the cart and remove them
- Increase/decrease the number of items in the cart
- See an order confirmation modal when they click "Confirm Order"
- Reset their selections when they click "Start New Order"
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- In desktop view, the order card should stick to the screen when users scroll down

Bonus
- Add attribute `amount` for each item in `data.json` to show the current of number of that item
- Implement logic to update the `amount` when order confirmed. No need to update via API, So it's mean if refresh the page the amount will be the same in API get items
- If which item out of stock (`amount` = 0) should display that product with disable UI and you can design by yourself
