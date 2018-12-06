
![Bootstrap 4 Layouts]

#Bootstrap 4 layouts

This repository is a template for a Bootstrap 4 website. It serves as a template reference for different bootstrap 4 layouts or to use as a theme for your site as is. You can see a live demo of the template at: [github-project-optimal.pensivewebstudio.com](http://www.github-project-optimal.pensivewebstudio.com).

You can see a live demo of a site that I build using this template at: [portfolio-item-optimal-structure.pensivewebstudio.com/](http://www.portfolio-item-optimal-structure.pensivewebstudio.com/).

It's based on a template by Ray Villalobos built for a LinkedIn learning course called [Bootstrap 4 Layouts: Responsive Single-Page Design](https://www.linkedin.com/learning/bootstrap-4-layouts-responsive-single-page-design/creating-a-bootstrap-4-layout?u=104). You can see a live demo of his project at: [raybo.org/bootstrap4layouts/](http://www.raybo.org/bootstrap4layouts/).

#Structure of the Layouts

The implementation is a single page design where each html article represents a page of the website, #page-about, #page-services etc… .. . I’ve named the articles #page-one, #page-two and so on to make the layout generic assuming you would want to rename them as you wish. For example, you could rename the article below: #page-about, if you wanted to make it your about page.

  <!-- #page-one -->
  <article id="page-one" class="page-icons page-section vertical-padding">

    <header class="page-section-header container">
      <h2 class="page-section-title display-4 pt-4 text-center">Page Section Title</h2>
      <p class="page-section-text lead mx-md-5">Page Section Text: Lorem Ipsum is simply dummy text of the
        printing and typesetting industry which will be replaced with text one you and your business upon completion
        of your site. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
        labore et dolore magna aliqua.</p>
    </header>

    <div class="layout-iconcolumns container vertical-padding">
      <div class="row text-center">

        <section class="col-md-4 my-3">
          <div class="icon-small layout-icon">
            <i class="fas fa-circle"></i>
          </div>
          <h3 class="layout-title">Layout Title</h3>
          <p class="layout-text">Layout Text: Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perspiciatis doloremque
            possimus dignissimos illo praesentium
            id consectetur tempora dolorum! Vel sapiente vitae, deserunt minima et rem accusamus?</p>
        </section>

        <section class="col-md-4 my-3">
          <div class="icon-small layout-icon">
            <i class="fas fa-square"></i>
          </div>
          <h3 class="layout-title">Layout Title</h3>
          <p class="layout-text">Layout Text: Dolorem repudiandae ipsa fugit distinctio modi earum dicta eum tenetur, vel temporibus
            laudantium totam libero
            odit ex labore commodi maiores molestias. Quo, hic maxime. Accusantium impedit dolorem cum error?</p>
        </section>

        <section class="col-md-4 my-3">
          <div class="icon-small layout-icon">
            <i class="fas fa-circle"></i>
          </div>
          <h3 class="layout-title">Layout Title</h3>
          <p class="layout-text">Layout Text: Et, alias asperiores? Repellat repudiandae, eum temporibus quibusdam iure, recusandae
            illo nesciunt, doloremque
            eligendi maiores tempora eos aliquid minus iusto ipsum facere. Minus, vitae autem dolores vero dolore?</p>
        </section>

      </div>
    </div>

  </article>
  <!-- #page-one 
------------------------------------------------------------>
```
Most layouts (not the floater layout) also have an optional `<header>`. They should be self-explanatory.


#Authors and Contributors

 Ray Villalobos: This project is based on a template by Ray built for a LinkedIn learning course called [Bootstrap 4 Layouts: Responsive Single-Page Design](https://www.linkedin.com/learning/bootstrap-4-layouts-responsive-single-page-design/creating-a-bootstrap-4-layout?u=104). You can see a live demo of his project at: [raybo.org/bootstrap4layouts/](http://www.raybo.org/bootstrap4layouts/).
