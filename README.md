# React Shopping Cart

# Step 1: Create React App

7. Cart Component
1- Set Active Task Management Spreadsheet
2- Create branch cart-component
3- Product.js
4- Handle "Add To Cart" to this.props.addToCart(product)
5- App.js
6- Add cartItems to state as []
7- Create addToCart(product)
8- Slice, Check product existance, add to cartitems
9- Cart.js

8. Chekout Form
1- Set Active Task Management Spreadsheet
2- Create branch checkout-form
3- Cart.js
4- Make cart items persistent
5- Use LocalStorage on App constructor to load cart items (JSON.parse)
6- Use LocalStorage on addToCart to save cart items (JSON.stringify)
7- Handle Click on Process
8- Update showCheckout state to true on click
9- Conditional rendering Checkout Form
10- Get email, Name and Address required input
11- Define handleInput function
12- Add Checkout Button
13- Handle onSubmit Form Event by this.createOrder
14- Create order object and pass to parent to handle it
15- Publish changes

9. Add Modal and Animation
1- Set Active Task Management Spreadsheet
2- Create branch animation-modal
3- Show animation
4- Install react-reveal
5- Create fade effect from bottom for products
6- Create fade left for add to cart
7- Create fade right for show checkout form
8- Open Modal by click on product image
9- Install react-modal
10- Product.js
11- Import Modal
12- Set state for product to null
13- Define openModal and closeModal
14- Show Modal if product exist
15- Create Modal
16- Create zoom effect for modal
17- index.css
18- Style Product Details
19- Commit and Publish changes
20- Pull request, merge, change to master
21- Task Management Spreadsheet set it done

10. Create Products Backend
1- Install nodemon globally
2- Add server.js
3- Install express(use as a web server) body-parser(to parse the data inside in post request to the server) mongoose(for connect to MongoDB) shortid(library for create userfriendly id to save products id)
4- Install MongoDB
5- app = express()
6- app.use(bodyParser.json())
7- mongoose.connect()
8- create Product model
9- app.post("api.products")
10- Postman send post request
11- route.get("/api/products")
12- route.delete("/api/products/:id")

