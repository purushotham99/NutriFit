<!--- The following README.md sample file was adapted from https://gist.github.com/PurpleBooth/109311bb0361f32d87a2#file-readme-template-md by Jahnavi Prasad for academic use --->

# Group 07 Project Proposal

## NutriFit
A Fitness app for users to look up new workouts and find or
come up with recipes that fit their diet.

* *Date Created*: 05 Jun 2024
* *Last Modification Date*: 24 Jun 2024
* *Git URL*: <https://git.cs.dal.ca/bontapalle/csci5709group07>
* *Deployed URL*: <https://csci5709s24group07.netlify.app>



## Authors

* [Mrunal Mangesh Patkar](mr396180@dal.ca) - Full Stack Developer, Designer, and Integrator
* [Poojitha Mummadi](pj589761@dal.ca) - Full Stack Developer, Tester
* [Purushotham Parthy](purushothamparthy@dal.ca) - Full Stack Developer, Documentation Manager
* [Rhushabh Rajkumar Bontapalle](rh364338@dal.ca) - Full Stack Developer, Documentation Manager
* [Rishi Varman Rathimala Thangaravi](rishivarman@dal.ca) - Full Stack Developer, Database Manager
* [Jahnavi Prasad Srirampurapu](jprasad@dal.ca) - Full Stack Developer, Copywriter, and Designer



## Deployment

The application is already deployed and is accessible at https://csci5709s24group07.netlify.app. The code was pushed to github and then deployed via Netlify.
 
Build command : ```npm run build```

## Built With

* [React JS](https://react.dev/learn) - The web framework used
* [Material-UI](https://mui.com/material-ui/getting-started/) - Implementing UI components from Google's Material Design
* [Web Vitals](https://web.dev/vitals/) - To measure the quality of User Experience
* [Emotion](https://emotion.sh) - Library to write css styles with JavaScript
* [React Router](https://create-react-app.dev/docs/getting-started/) - To handle routing in the React App
* [React Scripts](https) - To abstract the build setup of React App
* [@testing-library/react](https://testing-library.com/docs/react-testing-library/intro/) - to write unit and integration tests for React components

## Sources Used
 
#### Path: /src/pages/ContactForm.js
 
- Lines **82 - 91**
 
```
<iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2839.1116445955217!2d-63.59774862368475!3d44.63563508833893!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4b5a223075e6d9d7%3A0x748c455d10d45403!2sDalhousie%20University!5e0!3m2!1sen!2sca!4v1718755056897!5m2!1sen!2sca"
              width="500"
              height="500"
              style={{ border: 0 }}
              allowFullScreen=""
              loading="lazy"
              referrerPolicy="no-referrer-when-downgrade"
              title="Google Maps"
            ></iframe>
 
```
The code provided was developed by modifying the code found in the Google Maps Documentation. (https://developers.google.com/maps/documentation/embed/get-started)
 
```
<iframe
  width="600"
  height="450"
  style="border:0"
  loading="lazy"
  allowfullscreen
  referrerpolicy="no-referrer-when-downgrade"
  src="https://www.google.com/maps/embed/v1/place?key=API_KEY
    &q=Space+Needle,Seattle+WA">
</iframe>
 
```
**How code was implemented?**
 
The Google Maps embed code was implemented by integrating an iframe element into the ContactForm component. This required using the URL generated by the Google Maps Embed API, which allows embedding a fully interactive map into a web page. The iframe was configured with attributes to set the map's dimensions, styling, and additional parameters to ensure proper functionality and responsiveness.
 
**Why code was used?**
 
The Google Maps embed code was used to provide users with a visual reference of the location of Dalhousie University directly within the Contact Us page. This enhances user experience by allowing them to easily view and interact with the map without leaving the page. Embedding the map adds a professional touch to the contact page and provides necessary geographical context for users seeking to visit the physical location.
 
**How code was modified?**
 
The base embed code provided by the Google Maps Embed API was customized to fit the specific requirements of the application. Modifications included setting the width and height of the map to 500 pixels each, adding styling to remove the border, and configuring attributes such as allowFullScreen, loading, and referrerPolicy to optimize performance and user experience. The title attribute was added to improve accessibility by providing a descriptive title for the iframe content.


## Artificial Intelligence Tools Used
No AI Generated code was used in the making of this project.
However, we used ChatGPT to generate ideas for the App name and Logo.

* [ChatGPT](https://chatgpt.com/) - Used for non-coding purposes only.

### Prompt Used on ChatGPT

```
I'm creating an all-in-one fitness app that allows users to both track workouts and generate new healthy recipes. Come up with 15 potentials names for this app and what should I include in the logo.
```

## Acknowledgments

* We would like to thank the Internet, Google, and Prof. Gabriella Mosquera for the completion of this project proposal.