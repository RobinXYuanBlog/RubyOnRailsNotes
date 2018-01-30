## Welcome to RobinXYuan Rails Notebook

## Start an Application

## Controllers and Views

### Create Controllers

```Ruby
> rails g controller greeter hello
```

Then, go to ```project_dir/views/greeter/hello.html.erb```

*erb* => Embeded Ruby

ERB is a templating library (Similary to JSP, for example) that lets you embeded Ruby into your HTML file.

### Change Views

Then, in the *hello.html.erb* file, write

```Ruby
<% random_names = ["Alex", "Joe", "Michael"] %>
<h1>Greetings, <%= random.names.sample %></h1>
<p>The time now is <%= Time.now %></p>
```

<% ...Ruby codes... %> - Evaluate Ruby code
<%= ...Ruby codes... %> - Output evaluated Ruby code


