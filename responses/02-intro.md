## Create a User REST Interface

Representational State Transfer is a software style, 
that allows to create API (*Access Program Interface*); to consume
our builded Logic consistently.

For this exercise we would create an API that can allow people to create `Users` in a system and retrieve his informations.

So formally we would create a story that could look like:

<pre>
  <b>As</b> Developer<br/>
  <b>when</b> create a <b>GET</b> request at <b>/users</b><br/> 
  <b>then</b> I will recieve a list of users.<br/>
</pre>


So to close this issue you would need to:
 - Create a [Pull Request]({{ prUrl }})
 - Create the <b>Endpoint</b> `GET /users` and make the test pass.

*Remember that the list of User is empty.**
