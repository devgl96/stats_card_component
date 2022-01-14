# Frontend Mentor - Stats preview card component

![Design preview for the Stats preview card component coding challenge](./design/desktop-preview.jpg)

## The challenge

This challenge is to build out this card component and get it looking as close to the design as possible. 

I used the HTML and CSS for this challenge. I use the following features:
* HTML 
* Div (Classes selectors)
* Strong tag
* CSS
* Positions: Relative and Absolute
* Display: Grid and Flexbox
* Responsive layout

I learned a way to make the image has a color effect. In the challenge, I decided to use a different way, 
but I want to show this method that I found.

```html
    <div class="right-image-side fade-effect-image">
    </div>
```

```css
  .content .fade-effect-image {
      background-color: var(--accent-soft-violet);
      background-blend-mode: multiply;
    }

    .content .right-image-side {
      background-image: url("images/image-header-desktop.jpg");
      background-size: cover;

      width: 49.8%;
      height: 100%;

      border-radius: 0 10px 10px 0;
    }
```

**Have fun building!** 🚀
