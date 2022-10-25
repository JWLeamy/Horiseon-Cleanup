# Modified-Horiseon-Webpage

## Webpage Picture
![Image of modified Horiseon Webpage](./Develop/images/Horiseon.png)

## Technologies Used

1. HTML - used to create and structure the given webpage
2. CSS - used to modify the presentation and style of the given webpage
3. Git - used to clone down the original code prior to making modifications
4. Github - used to create this repository, modify and eventually commit each change made, and ultimately deploy the fully edited webpage. 

## Summary
The goal of this assignment was to use my newly developed HTML and CSS skillset to revise a set of code. While the original code displayed the same webpage image as seen above, it's format was unorganized, unsemantic, and contained many unnecessary lines of code. I fixed all of these issues without modifying the original layout of the webpage. 

## Steps
1. I carefully reviewed the many 'Div' tags included in the original code, and swapped them out accordingly to create a semantic HTML layout. (This included adding basic structure tags such as 'main', 'aside', 'section', 'footer', and more)
2. I cut out any class attributes, ID attributes, and other tags that took up space unnecessarily (also addded alt tags to images and icons).
3. Because I changed so many tags, I had to restructure the CSS style sheet to match the proper references. This not only meant adding changes, but deleted repetitive references.  
4. Aswell as carefully marking my progress within the code, I made sure to consistently commit my work to github with descreptive captions about my progress. 

Code Snippets HTML
```
Html
<Main class="content">
        <section class="card" id="seo">
            <img src="./Develop/images/search-engine-optimization.jpg" alt="SEO notepad img" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>
        <section class="card" id="orm">
            <img src="./Develop/images/online-reputation-management.jpg" alt="Rep management computer img" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </section>
        <section class="card" id="smm">
            <img src="./Develop/images/social-media-marketing.jpg" alt="Social Media img" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </section>
    </main>
    ```
    Code Snippet CSS
    ```
    /*No need to repeat the same code. Create a new class id named "benefit-card" and apply to all */
.benefit-card {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-card h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-card img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```