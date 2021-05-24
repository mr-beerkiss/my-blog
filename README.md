# My Blog

My Blog. It's based on Hugo and deployed using Netlify.  See the blog for details.

## Reminders

It's been so long since I posted I now need to remind myself how this all works.

To create a new post

```
hugo new posts/<post_name>
```

This will automatically create the file and insert the front-matter including `title`, `date` and
`draft`. By default `draft` is set to `false`. You'll need to set it to `true` when you want to 
publish it.

To preview content, start the server with 

```
hugo server -D
```
