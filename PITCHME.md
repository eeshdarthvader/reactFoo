### Cleartrip reactive journey from 3 to 0.2s using Apollo GraphQL
-------------

Case study: A GraphQL endpoint for Cleartrip to remove dependency of the client with Rest API.

---

## Hotel's Legacy code problems


- Page Load Time for hotel result page : ~ 4s
- Page size : ~2MB
- Same API's across the platform resulting in overfetching
- Overhead in maintaining different versions of API's
- Verbose response instead of derived data.
- Multiple API calls to fetch hotel results.

---

![Architechture Explained](https://res.cloudinary.com/cleartrip/image/upload/h_550/v1528778858/Cleartrip-Hotels-GraphQL_xzihtl.png)