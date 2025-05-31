<a name="readme-top"></a>

# SchoolSphere - Multipurpose School Management Dashboard

<!-- Table of Contents
<details>
<summary>

# Table of Contents

</summary>

- [Folder Structure](#bangbang-folder-structure)
- [Getting Started](#toolbox-getting-started)
- [Screenshots](#camera-screenshots)
- [Tech Stack](#gear-tech-stack)
- [Acknowledgements](#gem-acknowledgements)
- [Deploy on Vercel](#page_with_curl-deploy-on-vercel)

</details> -->

<!-- ## Folder Structure

Here is the folder structure of this app.

```bash
Full_Stack_Ecommerce_Website/
  |- backend/
    |-- config/
        |--- db.js
    |-- controllers/
        |--- categoryController.js
        |--- orderController.js
        |--- productController.js
        |--- userController.js
    |-- middlewares/
        |--- asyncHandler.js
        |--- authMiddleware.js
        |--- checkId.js
    |-- models/
        |--- categoryModel.js
        |--- orderModel.js
        |--- productModel.js
        |--- userModel.js
    |-- routes/
        |--- categoryRoutes.js
        |--- orderRoutes.js
        |--- productRoutes.js
        |--- uploadRoutes.js
        |--- userRoutes.js
    |-- utils/
        |--- createToken.js
    |-- index.js
  |- frontend/
    |-- /src
        |--- components/
            |---- CategoryForm.jsx
            |---- Header.jsx
            |---- Loader.jsx
            |---- Message.jsx
            |---- Modal.jsx
            |---- PrivateRoute.jsx
            |---- ProgressSteps.jsx
        |--- pages/
            |---- Admin/
                |----- AdminDashboard.jsx
                |----- AdminMenu.jsx
                |----- AdminRoute.jsx
                |----- AllProducts.jsx
                |----- CategoryList.jsx
                |----- OrderList.jsx
                |----- ProductList.jsx
                |----- ProductUpdate.jsx
                |----- UserList.jsx
            |---- Auth/
                |----- Login.jsx
                |----- Navigation.css
                |----- Navigation.jsx
                |----- Register.jsx
            |---- Orders/
                |----- Order.jsx
                |----- PlaceOrder.jsx
                |----- Shipping.jsx
            |---- Products/
                |----- Favorites.jsx
                |----- FavoritesCount.jsx
                |----- HeartIcon.jsx
                |----- Product.jsx
                |----- ProductCard.jsx
                |----- ProductCarousel.jsx
                |----- ProductDetails.jsx
                |----- ProductTabs.jsx
                |----- Ratings.jsx
                |----- SmallProduct.jsx
            |---- User/
                |----- Profile.jsx
                |----- UserOrder.jsx
            |---- Cart.jsx
            |---- Home.jsx
            |---- Shop.jsx
    |-- redux/
        |--- api/
            |---- apiSlice.js
            |---- CategoryApiSlice.js
            |---- orderApiSlice.js
            |---- productApiSlice.js
            |---- userApiSlice.js
        |--- features/
            |---- auth/
                |----- authSlice.js
            |---- cart/
                |----- cartSlice.js
            |---- favorites/
                |----- favoriteSlice.js
            |---- shop/
                |----- shopSlice.js
            |---- constants.js
            |---- store.js
    |-- utils/
        |--- cartUtils.js
        |--- localStorage.js
    |-- App.jsx
    |-- index.css
    |-- main.jsx
  |- .eslintrc.cjs
  |- .gitignore
  |- index.html
  |- package-lock.json
  |- package.json
  |- postcss.config.js
  |- tailwind.config.ts
  |- vite.config.js
```

<br /> -->

## Getting Started

1. Ensure **Git** and **NodeJS** are installed.
2. Clone this repository to your local machine.
3. Create `.env` file in the root directory.
4. Add the following environment variables to `.env`.

```bash
# .env

# Postgresql URI for connecting to the database
DATABASE_URL="postgresql://<database_name>:<database_password>@localhost:5432/school"

# next clerk credentials
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<CLERK_PUBLIC>
CLERK_SECRET_KEY=<CLERK_PRIVATE>
NEXT_PUBLIC_CLERK_SIGN_IN_URL= /

# next cloudinary credentials
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=xxxxxxxxx
NEXT_PUBLIC_CLOUDINARY_CLOUD_PRESET=xxxxxxxxxx

```

6. Open terminal in root directory. Run `npm install` or `yarn install`.

7. Now app is fully configured 👍 and you can start using this app using `npm run dev` or `yarn dev`.

<!-- ## Screenshots:

![Register Page](/screenshots/register.png "Register Page")
![Login Page](/screenshots/login.png "Login Page")
![Home Page](/screenshots/home.png "Home Page")
![Shopping Page](/screenshots/shop.png "Shopping Page")
![Cart Page](/screenshots/cart.png "Cart Page")
![Favorite Page](/screenshots/favorite.png "Favorite Page")
![Order Page](/screenshots/place-order.png "Order Page")
![Payment Page](/screenshots/payment.png "Payment Page")
![Shipping Page](/screenshots/ship.png "Shipping Page")
![Add Product Page](/screenshots/add-product.png "Add Product Page")
![Add Category Page](/screenshots/add-category.png "Add Category Page")
![Admin Dashboard Page](/screenshots/admin-dash.png "Admin Dashboard Page")
![Manage User Page](/screenshots/manage-user.png "Manage User Page")
![Manage Profile Page](/screenshots/manage-profile.png "Manage profile Page")
![All Products Page](/screenshots/all-products.png "All Products Page") -->

## Tech Stack

[![Typescript](https://skillicons.dev/icons?i=ts "Typescript")](https://www.typescriptlang.org/ "Typescript") [![PostgreSQL](https://skillicons.dev/icons?i=postgresql "PostgreSQL")](https://www.postgresql.org/ "PostgreSQL") [![React JS](https://skillicons.dev/icons?i=react "React JS")](https://react.dev/ "React JS") [![Node JS](https://skillicons.dev/icons?i=nodejs "Node")](https://nodejs.org/en "Node") [![NextJS](https://skillicons.dev/icons?i=nextjs "NextJS")](https://nextjs.org/ "NextJS") [![Tailwind CSS](https://skillicons.dev/icons?i=tailwind "Tailwind CSS")](https://tailwindcss.com/ "Tailwind CSS") [![Postman](https://skillicons.dev/icons?i=postman "Postman")](https://www.postman.com/ "Postman")

## Acknowledgements

Useful resources and dependencies that are used in SchoolSphere.

### Backend Dependencies

- [@clerk/nextjs](https://www.npmjs.com/package/@clerk/nextjs) - Version: ^5.4.1
- [@prisma/client](https://www.npmjs.com/package/@prisma/client) - Version: ^5.19.1
- [prisma](https://www.npmjs.com/package/prisma) - Version: ^5.19.1
- [zod](https://www.npmjs.com/package/zod) - Version: ^3.23.8

### Frontend Dependencies

- [next](https://www.npmjs.com/package/next) - Version: 14.2.5
- [react](https://www.npmjs.com/package/react) - Version: ^18
- [react-dom](https://www.npmjs.com/package/react-dom) - Version: ^18
- [react-big-calendar](https://www.npmjs.com/package/react-big-calendar) - Version: ^1.13.2
- [react-calendar](https://www.npmjs.com/package/react-calendar) - Version: ^5.0.0
- [recharts](https://www.npmjs.com/package/recharts) - Version: ^2.12.7
- [next-cloudinary](https://www.npmjs.com/package/next-cloudinary) - Version: ^6.13.0
- [moment](https://www.npmjs.com/package/moment) - Version: ^2.30.1
- [react-toastify](https://www.npmjs.com/package/react-toastify) - Version: ^10.0.5

### Development Dependencies

- [@types/node](https://www.npmjs.com/package/@types/node) - Version: ^20
- [@types/react](https://www.npmjs.com/package/@types/react) - Version: ^18
- [@types/react-dom](https://www.npmjs.com/package/@types/react-dom) - Version: ^18
- [@types/react-big-calendar](https://www.npmjs.com/package/@types/react-big-calendar) - Version: ^1.8.9
- [eslint](https://www.npmjs.com/package/eslint) - Version: ^8
- [eslint-config-next](https://www.npmjs.com/package/eslint-config-next) - Version: 14.2.5
- [tailwindcss](https://www.npmjs.com/package/tailwindcss) - Version: ^3.4.1
- [ts-node](https://www.npmjs.com/package/ts-node) - Version: ^10.9.2

<!-- ## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details. -->
