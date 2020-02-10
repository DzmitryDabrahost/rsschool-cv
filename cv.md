1.  Dzmitry Dabrahost
2.  phone: +375291148615, e-mail: dzmitrydabrahost@gmail.com
3.  My goal is to reach a high level in frontend, and eventually grow into a full-fledged Full-stack developer.
    To achieve my goal, I have such qualities as: thoroughness, accuracy, care, responsibility. 
    Knowing that my inaction can let the team or mentor down, I will not rest until I complete my part of the task.
    I don't like to put things off. I try to do everything as quickly as possible and on time.
    Now I am learning, and I am ready to learn and develop constantly.
4.  All at Junior level:
    HTML / CSS coding: HTML5, CSS3, Sass, Responsive and cross-browser coding
    JavaScript versions: ECMAScript 5-7
    Backend experience: Node.js
    Project builders: WebPack
    IDE: WebStorm, Visual Studio
    OS platforms: Windows, Linux (Ubuntu)
    GitHub systems: GitHub
5.  Code examples (LATEST) :
    
    My last project to JavaScript:

    ```function router() {
    const headerContainer = document.getElementsByClassName('header-container')[0],
          contentContainer = document.getElementsByClassName('content-container')[0],
          footerContainer = document.getElementsByClassName('footer-container')[0],
          header = new Header(),
          footer = new Footer();

    header.render().then(html => {
        headerContainer.innerHTML = html;
    });

    const request = Utils.parseRequestURL(),
        parsedURL = `/${request.resource || ''}${request.id ? '/:id' : ''}${request.action ? `/${request.action}` : ''}`,
        page = Routes[parsedURL] ? new Routes[parsedURL]() : new Error404();

    page.render().then(html => {
        contentContainer.innerHTML = html;
        page.afterRender();
    });

    footer.render().then(html => {
        footerContainer.innerHTML = html;
    });
}```

6-7.Courses IT-Academy 03/2019 - 05/2019 - Website development HTML, CSS, JavaScript;
    Courses IT-Academy 05/2019 - 09/2019 - JavaScript web application development
8.  English is my very big problem. I studied Spanish at school and Institute.
    Now I have been working with a tutor for 3 months to improve my English skills. I hope that by the time I am hired at EPAM, my English  level will be at the right level.