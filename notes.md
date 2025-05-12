

Q:
What line of code do you need to write in an Astro component’s frontmatter to receive values of title, author, and date as props?

A:
- const { title, author, date } = Astro.props;


Q:
How do you pass values as props to an Astro component?

A:
 - Import the component and then 
 
<BlogPost title="My First Post" author="Dan" date="12 Aug 2022" />
 - Use the component in your Astro page or another component, passing the values as attributes.

 