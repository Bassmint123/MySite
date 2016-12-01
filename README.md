# MySite

This is a Rails template that can be for sites that need to use persistance of certain sections.

In this example, the header and footer are persistent by using a partial file

The two partial files are _header.html.erb &  _footer.html.erb

In the application.html.erb file we are adding:
<body>
  <%= render "layouts/header" %>
    <%= yield %>
  <%= render "layouts/footer" %>  
  </body>

There are two pages that will render: 
1. welcome
2. second

Each page has a link to go back and forth between the two pages to see the persistance working.
