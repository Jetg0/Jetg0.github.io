---
layout: essay
type: essay
title: "Recreating Salvage Public’s Website with Bootstrap 5"
# All dates must be YYYY-MM-DD format!
date: 2024-10-08
published: true
labels:
  - Software Engineering 
---
---

#### Introduction

In the world of web development, recreating a website is a great way to learn new skills. I decided to take on the challenge of mimicking the Salvage Public website using Bootstrap 5. This choice offered an opportunity to work with a well known framework that promises faster development and responsive designs. In this essay, I’ll talk about why I chose Bootstrap 5, the struggles I faced during the process, and what I could improve on.

#### Why I Chose Bootstrap 5

Bootstrap 5 seemed like a good choice because it has a lot of built-in features that are supposed to help with making websites quickly and ensure they work on all devices. It comes with a lot of pre made components and designs that you can just plug into your website. However, using Bootstrap meant I had to learn a lot about its specific way of doing things, like using its grid system and figuring out how to override its default styles to match the unique look of Salvage Public.

#### Challenges I Faced

One of the main challenges was making sure the website looked just like the original Salvage Public site. Bootstrap’s default styles are pretty general and didn't match the specific style I needed. I spent a lot of time figuring out how to customize these styles, which required a deeper understanding of CSS than I expected. Another big challenge was making the site look good on all devices. Even though Bootstrap is built for responsiveness, I had to tweak a lot of things to get everything looking right on different screens.

The code below shows how much effort I put in for styling the footer for my mock up website <a href="https://salvagepublic.com/">here</a>.
Much more improvements could be made in the future with more precise coding.

```HTML
footer {
    font-size: 14px;
    color: #333;
    background-color: #f8f9fa;
    font-family: Arial, sans-serif;
    padding: 20px 0;
    text-align: center;
}

footer h5 {
    font-weight: bold;
    margin-bottom: 20px;
}

footer a {
    color: #333;
    text-decoration: none;
}

footer .btn-outline-dark {
    border-color: #333;
    color: #333;
    margin-top: 10px;
}

footer .btn-outline-dark:hover {
    background-color: #333;
    color: #fff;
}

footer .form-control {
    width: 50%;
    margin: 10px auto;
}

footer p {
    margin: 5px 0;
}

footer .links a {
    margin: 0 15px;
}

footer .social-icons a {
    margin: 0 10px;
}
```

Here's a comparison between the real vs. mock up website. Can you tell which is the real one?

<img src="https://github.com/user-attachments/assets/9aa6d4f0-044c-42e6-a79d-9ad0072e495f" alt="First image description" width="200" height="150">
<img src="https://github.com/user-attachments/assets/f2e789a9-1394-4dab-a73e-63dfef609e33" alt="Second image description" width="200" height="150">
<img src="https://github.com/user-attachments/assets/86a84070-2022-4132-bbb2-1443432c1d85" alt="Third image description" width="200" height="150">
<img src="https://github.com/user-attachments/assets/7d51cdba-9cab-4216-bb01-e1a8206accba" alt="Fourth image description" width="200" height="150">





#### What I Could Improve

Looking back, there are several things I could do better. For one, I could spend more time customizing the components to get even closer to the original design’s look and feel. I could also add more custom JavaScript to make the website more interactive and fun to use. Improving the site’s load times by optimizing images and only using the parts of Bootstrap that I really need would also help a lot. Plus, I could work on making the site better for search engines and more accessible to people with disabilities.

#### Conclusion

Recreating the Salvage Public website using Bootstrap 5 was a challenging but rewarding project. It taught me a lot about the framework and how to approach web development projects in general. I learned about the importance of customization, responsiveness, and optimization. I’m looking forward to using what I’ve learned in future projects and getting even better at creating websites that are both beautiful and functional.
