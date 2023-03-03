+++
description = "Sample documentation site for technical writers"
title = "Hugo for Documentation"

+++
{{< lead >}} I built this site with <a href="https://gohugo.io" target="_blank">Hugo</a>, a fast static website generator written in Go, that allows you to easily write well organized and clean documentation for your projects. {{< /lead >}}

## Features

This page shows the examples of some useful features for technical writers.

### How to add code block in Markdown table 
 
Use HTML table. 
 
<table> 
<tr> 
<td> Status </td> <td> Response </td> 
</tr> 
<tr> 
<td> 200 </td> 
<td> 
 
```json 
{ 
    "id": 10, 
    "username": "alanpartridge", 
    "email": "alan@alan.com", 
    "password_hash": "$2a$10$uhUIUmVWVnrBWx9rrDWhS.CPCWCZsyqqa8./whhfzBZydX7yvahHS", 
    "password_salt": "$2a$10$uhUIUmVWVnrBWx9rrDWhS.", 
    "created_at": "2015-02-14T20:45:26.433Z", 
    "updated_at": "2015-02-14T20:45:26.540Z" 
} 
``` 
 
</td> 
</tr> 
<tr> 
<td> 400 </td> 
<td> 
 
Markdown _here_. (Blank lines needed before and after!) 
 
</td> 
</tr> 
</table>

### Code Highlighting

This is an example of code highlighting.
{{< code lang="css" >}}
/* Typography styling */
.main > h1{
padding-top: 2rem;
}

.main > h2{
padding-top: 4rem;
margin-top:-1rem;  
}
{{< /code >}}

### Tables

#### Striped table

<table class="table table-striped">
<thead>
<tr>
<th scope="col">#</th>
<th scope="col">First</th>
<th scope="col">Last</th>
<th scope="col">Handle</th>
</tr>
</thead>
<tbody>
<tr>
<th scope="row">1</th>
<td>Mark</td>
<td>Otto</td>
<td>@mdo</td>
</tr>
<tr>
<th scope="row">2</th>
<td>Jacob</td>
<td>Thornton</td>
<td>@fat</td>
</tr>
<tr>
<th scope="row">3</th>
<td>Larry</td>
<td>the Bird</td>
<td>@twitter</td>
</tr>
</tbody>
</table>

#### Basic table

<table class="table">
<thead>
<tr>
<th scope="col">#</th>
<th scope="col">First</th>
<th scope="col">Last</th>
<th scope="col">Handle</th>
</tr>
</thead>
<tbody>
<tr>
<th scope="row">1</th>
<td>Mark</td>
<td>Otto</td>
<td>@mdo</td>
</tr>
<tr>
<th scope="row">2</th>
<td>Jacob</td>
<td>Thornton</td>
<td>@fat</td>
</tr>
<tr>
<th scope="row">3</th>
<td>Larry</td>
<td>the Bird</td>
<td>@twitter</td>
</tr>
</tbody>
</table>

**Bordered table**

<table class="table table-bordered">
<thead>
<tr>
<th scope="col">#</th>
<th scope="col">First</th>
<th scope="col">Last</th>
<th scope="col">Handle</th>
</tr>
</thead>
<tbody>
<tr>
<th scope="row">1</th>
<td>Mark</td>
<td>Otto</td>
<td>@mdo</td>
</tr>
<tr>
<th scope="row">2</th>
<td>Jacob</td>
<td>Thornton</td>
<td>@fat</td>
</tr>
<tr>
<th scope="row">3</th>
<td colspan="2">This is a column span</td>
<td>@twitter</td>
</tr>
</tbody>
</table>

**Hoverable rows**

<table class="table table-hover">
<thead>
<tr>
<th scope="col">#</th>
<th scope="col">First</th>
<th scope="col">Last</th>
<th scope="col">Handle</th>
</tr>
</thead>
<tbody>
<tr>
<th scope="row">1</th>
<td>Mark</td>
<td>Otto</td>
<td>@mdo</td>
</tr>
<tr>
<th scope="row">2</th>
<td>Jacob</td>
<td>Thornton</td>
<td>@fat</td>
</tr>
<tr>
<th scope="row">3</th>
<td> Larry</td>
<td> The Bird</td>
<td>@twitter</td>
</tr>
</tbody>
</table>

### YouTube

This is an example of YouTube video.

<iframe width="560" height="315" src="https://www.youtube.com/embed/lVXziMFEqX0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>