# Shoes E-Commerce

Shop made in Next.JS and Strapi containing products from https://nike.com

Repository: https://github.com/AndriyMakiyevskyi/NextJS_ShoesShop
## Features

- Image optimization by NextJS Image and Cloudinary
- Blazing fast page loading, very good SEO
- Products, discounts, images, etc. - all managed by Strapi CMS
- Reviews
- Payment with Stripe
- Sending emails using nodemailer
- Good looking animations

## Made using
- Next.JS
- Recoil
- GraphQL
- Strapi
- TailwindCSS
- Framer Motion
- Stripe
- Cloudinary

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`NEXT_PUBLIC_STRIPE_API_KEY`

`STRIPE_SECRET_KEY`

`STRAPI_IDENTIFIER` - strapi server user

`STRAPI_PASSWORD`

`NEXT_PUBLIC_STRAPI_URL`

`EMAIL_USER` - gmail user

`EMAIL_PASSWORD`

`PAGE_URL`

`NEXT_PUBLIC_CLOUDINARY_URL` (https://res.cloudinary.com/accountname/image/upload)
## Installation

Make .env.local file and paste variables from upper section, then install as normal Next.JS application.
