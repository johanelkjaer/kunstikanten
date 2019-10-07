---
works_index: true
hero_text: "<strong>We're Acme</strong>, we work for brands. But most importantly,
  we work for fun."
title: Hero

---
<Hero :text="$page.frontmatter.hero_text" />
<WorksList />

<form name="contact" netlify>

  <p>

    <label>Name <input type="text" name="name" /></label>

  </p>

  <p>

    <label>Email <input type="email" name="email" /></label>

  </p>

  <p>

    <button type="submit">Send</button>

  </p>

</form>