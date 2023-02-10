# My Portfolio Assignment

> assignment to complete week 4 - Frontend Infrastructure

Using week 3 for the content to deploy with netlify using local domain.

Assignment Link:

- http://rafajo.my.id
- https://rafajo.netlify.app

## Deployment Process

1. Connect the desired repo from github to netlify, for this assignment i use week 3 assignment as sample for the website layout. In this process the system will generate a subdomain with a random name followed by netlify.app on the address.
2. To change the domain name we can access it through domain setting. At production domains we can see your random subdomain given by default. Open the option then click “edit site name”. Here I change mine to rafajo.netlify.app.
3. Before connecting to the actual domain. We have to rent the domain, I bought it from local company idcloudhost.com. The domain name is rafajo.my.id.
4. After buying the domain, now we get back to netlify to connect the domain. Now we go to the same tab that we go to change our subdomain. There we click “add a domain”. The web will ask our domain. We enter the domain we bought from idcloudhost.com (rafajo.my.id)
5. From there just follow the instruction, after getting back to the domain setting tab now we setup our name server given by the instruction. There are 4 of them that copy that and get back to our idcloudhost.com client area and go to the “name server” option. Choose “custom name server” and then copy those 4 that we copied from netlify.
6. Before we go back to netlify go to the dns management option to change our www record to rafajo.netlify.app, our custom subdomain.
7. Now we go back to netlify and wait for the propagation process is completed. The propagation process completed when we see “check” icon with Netlify DNS label is appear at the right side of our domain name in te production domain tab.
