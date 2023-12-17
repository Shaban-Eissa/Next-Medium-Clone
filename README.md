# Next.js Medium Clone

<img src="https://github.com/Shaban-Eissa/Next-Medium-Clone/assets/49924090/72865f8a-08eb-40d7-963b-af9d430d8d8e" width="300" height="100" />


This is a Medium clone project built with Next.js, aiming to replicate the functionality and design of the popular online publishing platform.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)


## Features

- **Comments:** Enables users to comment on articles.
- **Responsive Design:** Ensures a seamless experience on various devices.

## Demo

<img src="https://github.com/Shaban-Eissa/Next-Medium-Clone/assets/49924090/ccb7fd06-7f66-4f75-89fc-c66b1a63c1f6" width="900" height="380" />
<br />
Check out the live demo https://next-medium-clone-sigma.vercel.app

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Shaban-Eissa/Next-Medium-Clone.git
   ```

2. **Install dependencies:**
    
    ```bash
    cd Next-Medium-Clone
    npm install
    ```

3. **Set up Sanity CMS:**
    
    * Create a Sanity account if you don't have one: [Sanity](https://www.sanity.io/)
    * Create a new project in the Sanity Studio.
    * Obtain your Sanity API Token and dataset name.
4. **Set up environment variables:**
    
    Create a `.env` file in the root directory and add the following environment variables:
    
    ```env
    NEXT_PUBLIC_SANITY_DATASET=your_sanity_dataset
    NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
    SANITY_API_TOKEN=your_sanity_api_token
    ```
    
    Replace `your_sanity_dataset`, `your_sanity_project_id`, and `your_sanity_api_token` with your actual Sanity CMS credentials.
    
5. **Run the Sanity Studio:**
    
    ```bash
    cd sanityyoutube
    sanity start
    ```
    
    This command will start the Sanity Studio, allowing you to manage your content.
       
6. **Run the development server:**
    
    ```bash
    npm run dev
    ```
    
7. **Open your browser:**
    
    Navigate to `http://localhost:3000` to see the Medium clone.
    

## Usage


    
* **Creating Articles:**
    
    Articles added with Sanity.io CMS .
    
* **Interacting with Articles:**
    
    Users can comment on articles
    

## Technologies

- Next.js
- Next-sanity
- Sanity CMS
- React-hook-form
- Tailwind CSS
- Typescript


## Contributing

Feel free to contribute by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated.
