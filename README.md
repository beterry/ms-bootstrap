# Developing a Marketo template styled with Bootstrap
A small project I designed to learn the development process of creating a Marketo guided template.

[Final project](https://go.themailshark.com/ben-playground.html)

[Full blog post](https://benterry.dev/blog/bootstrap-marketo/)

## Marketo guided templates

Marketo is an Adobe product. They provide services such as email marketing and lead management. At Mail Shark, the marketing department uses Marketo to build individualized landing pages to track response rates for direct mail campaigns. For example, if we were sending a piece of direct mail to a Marco’s Pizza franchise, the URL would be *themailshark.com/marcos* and lead to a landing page which would say, “Discounted pricing for Marco’s franchisees.” These landing pages also have unique analytic tools to help gauge the success of a campaign.

Guided templates in Marketo are pre-built landing pages with editable elements and variables. A team member without coding experience can easily create and customize a new landing page using a guided template.

As UI/UX Designer at Mail Shark, I often designed new guided templates, however, I wanted to learn the development process so I could implement better design patterns in the future.


### Why use Bootstrap?

This was my first experience using the Bootstrap CSS library. When I was first learning web development, I was told that I should first learn vanilla CSS, before using a framework, so I would better understand flexbox and grid. Now that I’m very comfortable with CSS, I was ready to see if Bootstrap, arguably the most well-known CSS library, would be helpful or a hindrance.

I thought this would be a good project to learn Bootstrap because Marketo guided templates are **only one** HTML file; any styling must be done inline and/or in a `<style>` tag in the `<head>` of the file. I expected that Bootstrap’s out-of-the-box utility classes may be handy to responsively style elements inline.

Also, these landing pages were usually expected to be developed quickly without much expectation of highly-custom components. Again, a great reason to use Bootstrap!
