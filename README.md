## Steps to run this project into your local machine

Things you need to run:- 

### `1.create-react-app`

You should have react development environment.

### `2.Json-Server`

The json-servor should be install to your machine.

#### `To intall and use json-servor follow the instruction`.

##### ``1.Installing Json-Servor``

**1.a):-** json-server is a node module, and hence can be installed globally by typing the following at the command prompt:
        **npm install json-server -g**


##### ``2.Configuring the Server``

**2.a):-** At any convenient location on your computer, create a new folder named json-server, and move to this folder.

**2.b):-** Download the [db.json](https://d3c33hcgiwev3.cloudfront.net/mNhQRT-6EeieJwrYiMRpMg_99c854b03fba11e8bac2b7a30cba3e24_db.json?Expires=1604534400&Signature=RJ4mSC00Tk74EWR-Kx7VL8d7C9J4CnEZEhSF8aJ~q-21Z6KvzZJq8x-ibmNuvOujmTw9sSFXf3d-Nlitxuu-jpx4Ug8DQAPmn0IFxasvUoYtRYjbaLBScPB2Pw0XX7BgFJeGrATtt4GP5peOmaHaSlh~XkqVia9CQEL8dZp3cpo_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A) file provided above to this folder.

**2.c):-** Move to this folder in your terminal window, and type the following at the command prompt to start the server:
          **json-server --watch db.json -p 3001 -d 2000**
         - This should start up a server at port number 3001 on your machine. The data from this server can be accessed by typing the following addresses into your browser address bar:
> - http://localhost:3001/dishes
> - http://localhost:3001/promotions
> - http://localhost:3001/leaders
> - http://localhost:3001/feedback
  
  - Type these addresses into the browser address and see the JSON data being served up by the server. This data is obtained from the db.json file.
  
  - The json-server also provides a static web server. Any resources that you put in a folder named public in the json-server folder above, will be served by the server at the following address:
  > http://localhost:3001/
  
  *(imp.)* **Shut down the server by typing ctrl-C in the terminal window.**


#### ``3.Serving up the Images``

**3.a):-** Create a public folder in your json-server folder.

**3.b):-** Download the [images.zip](https://d3c33hcgiwev3.cloudfront.net/dkYXuzfFEei9LwoRWz3xkg_77143c6037c511e8b2a51d62a734b875_images.zip?Expires=1604534400&Signature=YCUjllIoXR0cAaEJ8a8FfLp34sbvxMRK-RNvSHm0G9FeFZe-oYglxaYnK5c49UxeUnaDnrUdSQ23x5~WJaHek46DEBIReadrWkfpxTgujuRZ6z3hjMa2B6kspFCwx5mli9xyyRMkCeMuD2FTP~hZhvMqFl-n747lv66vZY81xQw_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A) file that we provide above, unzip it and move the images folder containing the images to the public folder.

**3.c):-** Restart the json-server as we did before. Now your server will serve up the images for our React app. You can view these images by typing the following into your browser address bar:
        **http://localhost:3001/images/image_name.png**
  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
