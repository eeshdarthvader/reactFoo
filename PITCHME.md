### Cleartrip reactive journey from 3 to 0.2s using Apollo GraphQL
-------------

A Case study

---

### A GraphQL endpoint for Cleartrip to remove dependency of the client with Rest API.

##### But Why introduce one more layer ?

---

### Hotel's Legacy code problems


- Page Load Time for hotel result page : ~ 4s
- Page size : ~2MB
- Same API's across the platform resulting in overfetching
- Overhead in maintaining different versions of API's
- Verbose response instead of derived data.
- Multiple API calls to fetch hotel results.

---

##### How to save time for API developers and remove their dependency ?
-------------

![Solution Explained](https://res.cloudinary.com/cleartrip/image/upload/v1529001281/solution_vbkrba.png)

---
![Architechture Explained](https://res.cloudinary.com/cleartrip/image/upload/h_550/v1528778858/Cleartrip-Hotels-GraphQL_xzihtl.png)