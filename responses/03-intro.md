### Add a `GET` and `CREATE** method to your rest.

We want to allow to Get users from our system, but before we want to do that, we would need to create.

So in this Step we gonna do two things:

**Create a user:**

<pre>
  <b>As</b> Developer<br/>
  <b>when</b> create a <b>POST</b> request at <b>/users</b><br/> 
  <b>then</b> I will recieve a the user created.<br/>
</pre>
later we would like to create a bit more complete [`data model`](https://en.wikipedia.org/wiki/Data_model)
but for now let's keep stuff symple our user would just have one property: `id`, this
property would just be the index of our `Array of users**.
So that first user would be `{ id: 0 }`

**Get user:**
<pre>
  <b>As</b> Developer<br/>
  <b>when</b> create a <b>GET</b> request at <b>/user/:id</b><br/> 
  <b>then</b> I will recieve a the user.<br/>
</pre>
Keep stuff symple, this means that a `GET` request would return `{ id: 0 }**.


**Important**
The endpoint `/users` that we previously created should stay be working 😉.

Hope steps are clears, now continue from this [PR]({{ prUrl }})
