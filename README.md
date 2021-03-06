## Candidate-Tester
This Repo is intended to instruct new Frontend developer (Native & Web) candidates on the steps to follow for completing the Norigin Media testing task.

---

#### What we want to assess:

* Your coding skills.
* Intuition for design & UX.
* Platform, Framework & Tooling knowledge.
* Packaging and production readiness.

#### Requirements :

 * Build a single screen of web or native application (**EPG Screen**) using your choice of framework / tooling
 
    **NOTE:** For *Web Developers*: React, Vue.js, React-Native, Vanilla JS, Angular2, Typescript for example - No restrictions apply.
    
    **NOTE:** For *Native Developers*: Java, Kotlin, ObjectiveC - No restrictions to tooling or frameworks apply.
 
 * Use the designs in the `./mockups` folder to guide your work. 
 * Use **Mock-Api** package included to supply the EPG data. See `package.json`.
 * For Web developers task submission is expected to be in NPM package format (**Preferably via GitHub**) with simple steps to install and run. Pass the link to your contact with our management or your recruiter when you're done. 
 
    **NOTE:** For *Native Developers*: Alternative methods of submission are acceptible for Android & iOS projects.
 
 * Task is not expected to take any more than 2 days of your time.

**NOTE:** There is no need to use this tester repo as the basis for your task. You can rework it, supply your own structure and include the libraries / dependencies however you prefer.

#### Cool to have (But not required and wont negatively impact assessment):

* Add more interactions, animations or just nail the UX.
* Additional screens using mock data api.
* Responsive layouts for multi-screen support.
* Make performance and optimization considerations.
* Go Nuts!


---
## Design Example:

We have included some mockup designs to act as a guide. You can find them in the `./mockups` folder.

Example EPG design:

![alt text](https://raw.githubusercontent.com/NoriginMedia/candidate-tester/master/mockups/EPG_small.png "Logo Title Text 1")



NOTE: Additional screens are optional and only if you really want to impress us with your skillz (Yes.. with a Z) should you add them to your app.

---

## Mock-API:

We have provided a basic mock api to supply EPG data for this task. 

This is packaged as a standard Node NPM module. To install simply run: `-> npm insall` from the project root directory.
Of course Node.JS should be installed beforehand. For Native Developers not familar with NPM here is the [NPM Documentation](https://docs.npmjs.com/getting-started/installing-node)

To run the mock-api server execute the command below:

```
-> npm run start:mock-api
```
You should see the server start on port 1337.
```
Mock service running at http://localhost:1337
```
You can now request data from the mock-api: 
`Try It: http://localhost:1337/epg`


For additional information you can find the package and the documentation here: [Norigin Mock-API](https://github.com/NoriginMedia/mock-api/tree/cloudberry)

---
