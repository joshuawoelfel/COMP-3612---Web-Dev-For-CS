# COMP 3612 (Fall 2021)
## Assignment #3: Node.js Web API Overview: Art Gallery APIs

#### Part of the design had to adhere to instructor specifications.
**Please view `COMP3612 Assignment 2.pdf` for full technical requirements.**

---

### Deployment Options:
- **Server Requirement:** This assignment requires a Node.js environment hosted on a server due to its dynamic nature.
- **Hosting Options:** Recommended hosting services include:
  - **Heroku:** Popular for its free tier and easy integration with GitHub. Requires CLI installation and setup.
  - **Digital Ocean:** Accessible through Git Education program for possible free credits.
  - **AWS or GCP:** Offers free credits but can be costly long-term. Suitable for those interested in DevOps.

### API Endpoints and Functionality:
- **General Endpoints:**
  - `/api/paintings`: Fetch all paintings.
  - `/api/artists`: Fetch all artists.
  - `/api/galleries`: Fetch all galleries.

- **Specific Endpoints:**
  - `/api/painting/id`: Fetch a single painting by its ID.
  - `/api/painting/gallery/id`: Fetch paintings by gallery ID.
  - `/api/painting/artist/id`: Fetch paintings by artist ID.
  - `/api/painting/year/min/max`: Fetch paintings within a specific year range.
  - `/api/painting/title/text`: Fetch paintings by title (case insensitive).
  - `/api/painting/color/name`: Fetch paintings by color name in hex (case insensitive).
  - `/api/artists/country`: Fetch artists by country (case insensitive).
  - `/api/galleries/country`: Fetch galleries by country (case insensitive).

### Error Handling:
- **Not Found Conditions:** APIs must handle cases where the queried ID or parameter does not exist, returning an appropriate JSON message indicating no data was found.

### Additional Requirements:
- **No Third-Party Libraries:** Use of native JavaScript is expected. If using small snippets of online code, provide references in the source code.

### Performance Tips:
- **Early Setup:** Arrange and test hosting well before the assignment deadline to ensure functionality and accessibility.

### Following links were provided for testing the API:
https://stormy-basin-47606.herokuapp.com/paintings

https://stormy-basin-47606.herokuapp.com/painting/433

https://stormy-basin-47606.herokuapp.com/painting/43374534856

https://stormy-basin-47606.herokuapp.com/painting/gallery/7

https://stormy-basin-47606.herokuapp.com/painting/gallery/43374534856

https://stormy-basin-47606.herokuapp.com/painting/artist/106

https://stormy-basin-47606.herokuapp.com/painting/artist/43374534856

https://stormy-basin-47606.herokuapp.com/painting/year/1850/1900

https://stormy-basin-47606.herokuapp.com/painting/year/2200/2400

https://stormy-basin-47606.herokuapp.com/painting/title/self

https://stormy-basin-47606.herokuapp.com/painting/title/dfjkghdfkgh

https://stormy-basin-47606.herokuapp.com/painting/color/NAPA

https://stormy-basin-47606.herokuapp.com/painting/color/coffee%20bean

https://stormy-basin-47606.herokuapp.com/painting/color/kcvhvxchbkcj

https://stormy-basin-47606.herokuapp.com/artists

https://stormy-basin-47606.herokuapp.com/artists/Netherlands

https://stormy-basin-47606.herokuapp.com/artists/sdfjjsdf

https://stormy-basin-47606.herokuapp.com/galleries

https://stormy-basin-47606.herokuapp.com/galleries/france

https://stormy-basin-47606.herokuapp.com/galleries/kcvhvxchbkcj

---





  
