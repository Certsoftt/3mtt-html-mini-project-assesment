# Project Overview
A simple webpage structure designed using only HTML semantic element to implement 
1. Accessibility, better seo
2. Better SEO
3. Easy maintenance and readability
4. Consistent styling and robust nature

## Here’s Project Design outline:
The web page has three sections:
- [x] Header Section
- [x] Main Section, and
- [x] Footer Section

## Step-by-Step Implementation Of Project Design
1. ### Header Section Implementation:<br/>
The Header section contains the navigation menu which is semantically implemented using `<header>`, `<nav>`, and `<ul>` HTML element with a heading or sub-heading html element that describe what section it is as shown below:

 ```html
      <header>
            <h1>My Profile</h1>
            <nav>
                <ul>
                    <li><a href="#">About Me</a></li>
                    <li><a href="#">Hobbies</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </header>
```
1. The `<header>` html element used as an overall wrapper or self-contained unit to indicate where the header section starts and stops
2. The `<nav>` html element is used to indicate the self-contained unit that implements the navigation menu
3. The `<ul>` html element is responsible for holding the list of the navigation menus
4. The `<li>` html element holds the links to each of the navigation menu. Indirectly it is the element where you can nest your `<a>` html element
5. The `<a>` html element is responsible for linking the text that describe each of the navigation menu.

2. ### Main Section Implementation:<br/>
This section holds the rest of the content of the webpage excepts the content that should be at the footer section.
This section uses semantic element such as:
1. `<p>` html element for text
2. `<section>` html element for organizing content into respective semantic structure and self-contained unit for easy code readability
3. `<ol>` html element for listing out the hobbies
4. `<img>` html element for visual display of photos and pictures
5. `<h2>` html element for giving a descriptive sub-heading for each sections
6. `<main>` html element as the overall wrapper or self-contained unit that indicate where the main section starts and stops.

```html
        <main>
            <section>
                <h2>About Me</h2>
                <img src="https://media.licdn.com/dms/image/v2/D4D03AQGVPOL3MN1Obg/profile-displayphoto-shrink_200_200/B4DZQ9.7SqGkAY-/0/1736206695897e=1746662400&v=beta&t=t0gPMDJaAXyaz3TsvH4W3HMqVQ6LNd9DbA75XPh0Fs0" alt="Ubong's Ukpe profile" loading="lazy" width="150px" height="150px"/>
                <p>
                    Experienced, performance and result driven Software 
                    Application Developer who diligently monitors managing database and a robust 
                    programmable system to achieve the desired result.
                </p>
            </section>
            <section>
                <h2>Hobbies</h2>
                <ol>
                    <li>Football &#9917;</li>
                    <li>Computer Game &#127918;</li>
                    <li>Chess &#x2654;</li>
                </ol>
            </section>
        </main>
```

3. ### Footer Section Implenetation:<br/>
This section contains the contact details and social media handles. To implement such, the following elements were used:
1. `<button>` html element to depict a CTA and interaction for user interested to get intouch
2. `<svg>` html element to implement robust and consistent cross-platform visual appealing icon display for each social media handles
3. `<a>` html element to provide the link for each social media handles and ways to get intouch
4. `<footer>` html element as the overall wrapper or self-contained unit that indicate where the footer section starts and stops.

```html
        <footer>
            <h3>Get In touch</h3>
            <button>
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-envelope" viewBox="0 0 16 16">
                  <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1zm13 2.383-4.708 2.825L15 11.105zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741M1 11.105l4.708-2.897L1 5.383z"/>
                </svg>
                <a href="mail:atmonidexz@gmail.com">atmonidexz@gmail.com</a>
            </button>
            <button>
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-whatsapp" viewBox="0 0 16 16">
                  <path d="M13.601 2.326A7.85 7.85 0 0 0 7.994 0C3.627 0 .068 3.558.064 7.926c0 1.399.366 2.76 1.057 3.965L0 16l4.204-1.102a7.9 7.9 0 0 0 3.79.965h.004c4.368 0 7.926-3.558 7.93-7.93A7.9 7.9 0 0 0 13.6 2.326zM7.994 14.521a6.6 6.6 0 0 1-3.356-.92l-.24-.144-2.494.654.666-2.433-.156-.251a6.56 6.56 0 0 1-1.007-3.505c0-3.626 2.957-6.584 6.591-6.584a6.56 6.56 0 0 1 4.66 1.931 6.56 6.56 0 0 1 1.928 4.66c-.004 3.639-2.961 6.592-6.592 6.592m3.615-4.934c-.197-.099-1.17-.578-1.353-.646-.182-.065-.315-.099-.445.099-.133.197-.513.646-.627.775-.114.133-.232.148-.43.05-.197-.1-.836-.308-1.592-.985-.59-.525-.985-1.175-1.103-1.372-.114-.198-.011-.304.088-.403.087-.088.197-.232.296-.346.1-.114.133-.198.198-.33.065-.134.034-.248-.015-.347-.05-.099-.445-1.076-.612-1.47-.16-.389-.323-.335-.445-.34-.114-.007-.247-.007-.38-.007a.73.73 0 0 0-.529.247c-.182.198-.691.677-.691 1.654s.71 1.916.81 2.049c.098.133 1.394 2.132 3.383 2.992.47.205.84.326 1.129.418.475.152.904.129 1.246.08.38-.058 1.171-.48 1.338-.943.164-.464.164-.86.114-.943-.049-.084-.182-.133-.38-.232"/>
                </svg>
                <a href="https://wa.me/08148106698?text=Hello!" target='_blank'>Chat on WhatsApp</a>
            </button>
            <button>
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16">
                  <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"/>
                </svg>
                <a href="https://linkedin.com/in/ubong-sunday-ukpe" target="_blank">View My LinkedIn Profile</a>
            </button>
        </footer>
```

## Important Notes On Code Practice
- ### Accessibility & Optimization:<br/>
1. `<img>` html element should have `alt` attribute that provides an alternative text for screen users and machines, and `loading` attribute to enable `lazy` loading and optimization
2. The text used to display links in `<a>` html element should a clarity on what the point to and not a generic approach like using "click here", rather use "read more", "chat up on whatsapp" and so on.
   
- ### Consistent Styling & Robustness:<br/>
1. `<img>` html element should have a specified dimensions to prevent layout shifts on cross-platforms
2. `<img>`, `<svg>`, or HTML Unicode or Entity should be used when trying to include an icon or emoji in html rather than directly using an icon symbol or emoji which this can cause inconsistentcy when accessed using cross-platforms.
3. Use of consistent headings html element pattern.

- ### Better SEO:<br/>
1. It is best that a web page contains only one(1) `<h1>` html element and a hierarchical inclusion of sub-headings from `<h2>` to `<h6>`.

- ### Readability & Maintenability:<br/>
1. The use of semantic element and less of non-semantic element to enhance code clarity and maintenability
2. Easy to maintain a cohesive design and the use of global styles across different pages when semantic elements are in used.

