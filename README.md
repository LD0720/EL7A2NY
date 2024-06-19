# El7a2ny System


# Clinic System 
The theme of the project is to create a clinic System integrated with a pharmacy system. The system make the book an appointment and upload his/her medical history files also to communicate with the doctor incase any problem occured. Existing web application include but are not limited to vezeeta.


# Motivation
**The following are the objectives of this project:**
* Master working with *MERN Stack*.
* Work using the Agile Methodology to plan out a project and develop the software throughout different sprints.
* Practice working together as a team on GitHub.
* Learn the process of following a given set of System Requirements to develop a software. 


# Build Status
The project is fully functioning. But , for the user's optimal satisfaction some of the backend functonalities may need to be enhanced. Also , the UX might need further work.

# How to run
in clinic:
    in frontend:
    .env:
        REACT_APP_BASE_URL=http://localhost:4000
        REACT_APP_PHARMACY_BASE_URL=http://localhost:3002
        REACT_APP_BASE_ZEGO_APP_ID=54571839
        REACT_APP_BASE_ZEGO_SERVER_SECRET=5918a689e914a1074c1f7a66c70a63c2

    in backend:
        .env:
            PORT=4000
            MONGO_URI=mongodb+srv://lobna20desouky:guc-Vclinic@cluster0.ytpdtrh.mongodb.net/?retryWrites=true&w=majority
            SECRET_KEY=SECRETKEYKEYSECRET
            STRIPE_KEY=sk_test_51O5VGzLURTC53ByJgV0KeMquJXcUqPLu40UK6QmyV6zGu5fgpSOV3ZP6jaDbeHtgZdvV06aGHOlLFRMOpGEMkncN00GwYbKqZ7
            STRIPE_SUCCESS=http://localhost:3001/checkout-success
            STRIPE_SUCCESS_APPOINTMENT=http://localhost:3001/checkout-success-appointment
            STRIPE_FAIL=http://localhost:3000/


  3- to start the project please be sure to start all of the following instance
  in clinic:
  in frontend: cd frontend >> npm install >> npm install dotenv >> npm start
  in backend: cd backend >> npm install >> npm install dotenv >> npm start
        and always start clinic frontend after pharmacy to start clinic on localhost:3001 to start navigating the app

# Code Style
### General Rules
We, mainly used standard code style throughout the whole code. Some of the rules we followed include but are not limited to:
* Readability counts.
* Be consistent.
* [Don't repeat yourself](http://en.wikipedia.org/wiki/Don't_repeat_yourself).
* Flat is better than nested.
* Beautiful is better than ugly.
* Simple is better than complex.
* Add blank line to the end of every file.
* Limit lines to 80 characters.


### JavaScript
* Two spaces indentation.
* Single quotes are preferred over double. Reason: HTML uses double quotes.
* Write code in functional style with minimum side effects.
* Don't use function statements. Instead, create anonymous functions and
assign them to consts for consistency with other consts.

    ```javascript
    // No
    function doThing(a, b) {return a * b;}

    // Yes
    const doThing = function(a, b) {return a * b;};
    ```

* Do not use quotes in object keys.

    ```javascript
    // No
    {'a': 'testtest'}

    // Yes
    {a: 'testtest'}
    ```

### HTML
* Two spaces indentation.

### CSS
* Two spaces indentation.
* Use lowercase hex colors (e.g. #fff) instead of color names (e.g. white).
* [Use `* {box-sizing: border-box;}`](http://paulirish.com/2012/box-sizing-border-box-ftw/).
* Use hyphens between class names, not camelCase or under_scores.
* Use only classes for styling most of the time (no #ids, elems etc).
* Don't use inline styling.
* Profile your selectors with webkit inspector.
* Use tree-style indentation.

    ```css
    .signup-page {
      background: #0d0; }
      .signup-button {
        padding: 10px;
        background-image: url("../img/signup.png"); }

    /* This looks cool if you use Stylus etc. */
    .chat-page {
      font-size: 0.9em; }
      .identity {
        margin-bottom: 20px; }
        .identity-profile {
          height: 4em; }
        .identity-nickname {
          float: left;
          width: 165px; }
        .identity-avatar {
          float: right; }
        .identity-updates {
          margin-top: 10px; }
        .identity-status {
          height: 30px; }
        .identity-current-mood {
          padding-left: 5px; }
        .identity-button {
          float: right; }
    ```

* Use this sequence of properties

    ```css
    .item {
      position: static;
      z-index: 0;
      top: 0;
      right: 0;
      bottom: 0;
      left: 0;

      display: block;
      visibility: hidden;
      float: none;
      clear: none;
      overflow: hidden;
      clip: rect(0 0 0 0);

      box-sizing: content-box;
      width: auto;
      min-width: 0;
      max-width: 0;
      height: auto;
      min-height: 0;
      max-height: 0;
      margin: 0;
      padding: 0;

      table-layout: fixed;
      empty-cells: show;
      border-spacing: 0;
      border-collapse: collapse;
      list-style: none;

      font: 1em sans-serif;
      font-family: Arial, sans-serif;
      font-size: 1em;
      font-weight: normal;
      font-style: normal;
      font-variant: normal;

      content: "";
      cursor: default;
      text-align: left;
      vertical-align: top;
      line-height: 1;
      white-space: normal;
      text-decoration: none;
      text-indent: 1;
      text-transform: uppercase;
      letter-spacing: 1;
      word-spacing: normal;

      opacity: 1;
      color: #d00;
      text-shadow: 5px 5px 5px #d59;
      border: 1px solid #d00;
      border-radius: 15px;
      box-shadow: inset 1px 0 0 #fff;
      background: #fff url("../i/bg.png") no-repeat 0 0; }
    ```


    
# Tech/ Framework Used

**We used *MERN Stack* framework to create this Web Application**. MERN stack is a software stack that includes four open-source technologies: (MongoDB, Express.js, React, and Node.js). These components provide an end-to-end framework for building dynamic websites and web applications.



##### Database 
* [Mongo DB](https://www.mongodb.com/) - The only database that harnesses the innovations of NoSQL. MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas. MongoDB is developed by MongoDB Inc. and licensed under the Server Side Public License.

* [Firebase Storage](https://console.firebase.google.com/) - as a cloud storage for files.

##### Node.js Framework
* [Express JS](http://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js.Express.js, or simply Express, is a back end web application framework for Node.js that is released as free and open-source software under the MIT License. It is designed for building web applications and APIs. It has been called the de facto standard server framework for Node.js.

##### Frontend
* [React JS](https://reactjs.org/) - A declarative, efficient, and flexible JavaScript library for building user interfaces.React is a free and open-source front-end JavaScript library for building user interfaces based on UI components. It is maintained by Meta and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

##### Backend
* [Node JS](http://nodejs.org/) - A platform built on Chrome's JS runtime for easily building fast, scalable network apps. Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.

#### other used technologies 
The used packages and technologies with-in the app:

    Mongoose as a DB handler package for node and react.
    Tailwind css as a css-provider for the app.
    React-Redux as a state manager for the app.
    ZegoCloud as a video provider.
    Js-PDF as a package for handling PDF files in the app.
    React-Image-Gallery as a picture handler.
    Node mailer as a mailing service.
    Stripe as a Payment Handler.
    Otp-generator for OTP services.
    Json-web-token for handling authentications.
    Express.js for handling APIs.
    CORS for handling network.
    DOTENV for handling .env files.
    bcryptjs for hashing passwords,
    firebase-admin for sending notification via firebase from backend,
    nodemailer for sending mails,
    otp-generator for generating otps and verify,


# Required Installations
### [Visual Studio Code](https://code.visualstudio.com/download)
### [Node](https://nodejs.org/en/download/)
### Libraries & Framework
All commands needed to install all required libraries and frameworks can be found at [npm website](https://www.npmjs.com/).
//TODO : edit references
# API References
#### [Stripe API](https://stripe.com/docs/api)
We are planning onto using this api in order to test paying with credit cards on our website.

# Tests
We usually tested our backend using [Postman](https://www.postman.com/downloads/), and we tested our frontend by running it using the command *npm start* in the frontend using the command line. It is also good to know that backend functionality can be tested using jtests, yet we prefered using the other methods mentioned above.


curl --location 'http://localhost:4000/Admin/createAdmin' \
--header 'Content-Type: application/json' \
--data '{
    "userName": "",
    "password": "",
    "email": ""
}'

# API Referencs      
This is a navigation map to the app
    # Post :
        "/Doctor/addPrescription"
        "/Doctor/respondToAppointmentRequest"
        "/Doctor/addDoctorPatients"
        "/Patient/addFamilyMember"
        "/contract/createContract"
        "/otp/send"
        "/otp/verify"
        "/appointments/createAppointment"
        "/Admin/createAdmin"
        "/pay/checkout-stripe"
        "/pay/payForAppointment"
        "/availability/createAvailability"
        "/healthPackage/addPackage"
        "/healthPackage/payByWallet"
        "/auth/login"
        "/auth/registerPatient"
        "/auth/registerDoctor"
        "/auth/resetPassword"
        "/auth/changePassword"
        "/medicalHistory/add"

    # Put:

        "/Doctor/updatePrescription"
        "/Doctor/updateDoctors"
        "/Patient/updatePatient"
        "/Patient/updateWallet"
        "/Patient/addPrescriptionsToPatient"
        "/Patient/createAppointment"
        "/appointments/updateStatus"
        "/Admin/respondDoctorRequest"
        "/healthPackage/updatePackage"
        "/healthPackage/subscribe"
        "/healthPackage/unSubscribe"
        "/auth/respondContract"

    # Get : 

        "/Doctor/getAllDoctors"
        "/Doctor/getDoctorById"
        "/Doctor/getAllPatients/:id"
        "/Doctor/searchPatients"
        "/Doctor/doctors/:doctorId/upcoming-appointments"
        "/Doctor/getPatientById"
        "/Doctor/viewPatient/:id"
        "/Doctor/getDoctorPatients"
        "/Doctor/getAppointments"
        "/Doctor/getAvailableAppointments"
        "/Doctor/filterAppointments/:id"
        "/Doctor/filterUpcomingAppointments/:id"
        "/Patient/getFamilyMembers"
        "/Patient/getAllPatients"
        "/Patient/getHealthPackages"
        "/Patient/getPatientById/:id"
        "/Patient/getPrescription"
        "/Patient/getAllDoctorsWithPrices"
        "/Patient/getPatientDoctors"
        "/contract/getContract"
        "/appointments/appointments"
        "/Admin/getAllAdmins"
        "/Admin/getDoctorsRequests"
        "/availability/getAvailabilityById"
        "/healthPackage/getAllPackages"
        "/deduction/get"

    # Delete :
        "/Doctor/DeleteDoctor/:id"
        "/Patient/deletePatient/:id"
        "/appointments/deleteAppointment/:id"
        "/Admin/removeUser"
        "/Admin/deleteAdmin/:id"
        "/healthPackage/deletePackage"


# code examples
### create availability

const createAvailability = async (req, res) => {
  try {
    const { doctorId, date, fromTime, toTime } = req.body;
    var availability = await Availability.findOne({
      doctor: doctorId,
      date: new Date(date),
      fromTime,
      toTime
    });
    
    if(availability)
    {
      return res.status(400).json({success:false, message:"you have an existing availability time with this data"});
    }
    availability = new Availability({
      doctor: doctorId,
      date: new Date(date),
      fromTime,
      toTime
    });

    const savedAvailability = await availability.save();

    res.status(200).json({data:savedAvailability, success:true});
    const doctor = await DoctorsModel.findById(doctorId);
    const newAvailability = doctor.availability;
    newAvailability.push(savedAvailability);
    doctor.availability = newAvailability;
    await DoctorsModel.findByIdAndUpdate(doctorId, {
      availability: newAvailability,
    });
  } catch (error) {
    console.error(error);
    res.status(500).json({ message: "Server error" });
  }
};


### send otp
const sendOTP = async (req, res) => {
	const { email } = req.body;

	let user = await AdminsModel.findOne({ email });
	if (!user) {
		user = await DoctorsModel.findOne({ email });
	}
	if (!user) {
		user = await PatientsModel.findOne({ email });
	}
	if (!user) return res.status(401).json({ message: 'Wrong email' });

	var OTP = OTPGenerator.generate(6, {
		upperCaseAlphabets: false,
		lowerCaseAlphabets: false,
		specialChars: false,
	});
	try {
		var result = await OTPUserModel.create({
			userEmail: email,
			OTPCode: OTP,
		});

		if (result) {
			await sendEmail(email, `this is your OTP code ${OTP}`, 'Otp Verification', emailResult => {
				if (emailResult) {
					res.status(200).json({
						OTP,
						message: 'Otp sent successfully',
						isSent: true,
						email,
					});
				} else {
					res.status(500).json({
						OTP,
						message: 'Otp not sent successfully',
						isSent: false,
					});
				}
			});
		}
	} catch (e) {
		console.error(e);
		res.status(500).json({ message: 'Server Error' });
	}
};

### respond to contract
 const respondToContract = async (req, res) => {
  try{
  const {id, accepted} = req.body

  var doctor = await DoctorsModel.findOne({_id:id});
  if(doctor)
  {
    if(accepted === true){
      doctor.contract.accepted = true;
      doctor.save().then(rsp=> 
        res.status(200).json({ success:true,data:{message: "contract accepted"} })
        );
    }else if(accepted === false)
    {
      ContractsModel.deleteOne({_id: doctor.contract.myContract}).then(rsp=> 
        res.status(200).json({ data:{message: "contract rejected and deleted"} })
        );
    }
  }
  }catch (error) {
    console.log(error.message)
    return res.status(500).json({ message: error.message });
  }
}


# screenshots : 
### admin account : https://github.com/advanced-computer-lab-2023/Whatthescrum-Clinic/blob/c4d580919f10ca07d4720baf70fcda90709a19ad/admin%20account.png
### clinic login : https://github.com/advanced-computer-lab-2023/Whatthescrum-Clinic/blob/c4d580919f10ca07d4720baf70fcda90709a19ad/clinic%20login.png
### doctor communication : https://github.com/advanced-computer-lab-2023/Whatthescrum-Clinic/blob/c4d580919f10ca07d4720baf70fcda90709a19ad/doctor%20communication.png
### patient home page : https://github.com/advanced-computer-lab-2023/Whatthescrum-Clinic/blob/c4d580919f10ca07d4720baf70fcda90709a19ad/patient%20home%20page.png


# Features : 
  patient : 
    view doctors , select a certain appointment , filter doctors and appointments , view presctiptions , purchase a prescription , chat with doctor and pharmacist, add address , view cart and edit cart 

 doctor : 
	view patients , filter patients , update appointment status , add availability, write , edit and export prescriptions.


# Required Installations
### [Visual Studio Code](https://code.visualstudio.com/download)
### [Node](https://nodejs.org/en/download/)
### Libraries & Framework
All commands needed to install all required libraries and frameworks can be found at [npm website](https://www.npmjs.com/).

# Contribute
Any contributions are highly appreciated as this is our first MERN Stack application, and we would love to learn and develop more.

# Credits
Special credits go to **CSEN704 Advanced Computer Lab Course Team**: *Assoc. Prof. Mervat Abuelkheir, Eng. Noha Hamid, Eng. Nada Ibrahim , Eng. Fatma Hosam , Eng. Amr Diab, Eng. Mabrook and Eng. Hadwa Pasha* at the Faculty of Media Engineering and Technology in The German University in Cairo. We, also, want to thank [**The Net Ninja**](https://www.youtube.com/@NetNinja) Youtube channel as we obtained a lot of information from its playlist [MERN Stack Crash Course Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iJ_KkrkBZWZRHVwnzLIoUE).



# License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)(https://stripe.com/docs/api) (www.zegoCloud.com)


# Pharmacy System 
The theme of the project is to create a pharmacy System integrated with a clinic system.The system make the patient able to purchase his/ her prescription automatically when the doctor prescribes it. Existing web application include but are not limited to vezeeta.


# Motivation
**The following are the objectives of this project:**
* Master working with *MERN Stack*.
* Work using the Agile Methodology to plan out a project and develop the software throughout different sprints.
* Practice working together as a team on GitHub.
* Learn the process of following a given set of System Requirements to develop a software. 


# Build Status
The project is fully functioning. But , for the user's optimal satisfaction some of the backend functonalities may need to be enhanced. Also , the UX might need further work.

# How to run
in frontend:
    .env:
        REACT_APP_CLINIC_BASE_URL=http://localhost:4000
        REACT_APP_BASE_URL=http://localhost:3002
in backend:
    .env:
        PORT=3002
        MONGO_URI=mongodb+srv://Pharmacy:Pharmacy@pharmacy.718vudy.mongodb.net/?retryWrites=true&w=majority
        SECRET_KEY=SECRETKEYSECRETKEYSECRETKEYSECRETKEY
        STRIPE_KEY=sk_test_51O5VGzLURTC53ByJgV0KeMquJXcUqPLu40UK6QmyV6zGu5fgpSOV3ZP6jaDbeHtgZdvV06aGHOlLFRMOpGEMkncN00GwYbKqZ7
        STRIPE_SUCCESS=http://localhost:3000/checkout-success
        STRIPE_FAIL=http://localhost:3000/
- to start the project please be sure to start all of the following instance
    in pharmacy:
    to run frontend : cd frontend >> npm install >> npm install dotenv >> npm start
    to run backend  : cd backend  >> npm install >> npm install dotenv >> npm start
        and always start pharmcy frontend first to start on localhost:3000 to start navigating the app

# Code Style
### General Rules
We, mainly used standard code style throughout the whole code. Some of the rules we followed include but are not limited to:
* Readability counts.
* Be consistent.
* [Don't repeat yourself](http://en.wikipedia.org/wiki/Don't_repeat_yourself).
* Flat is better than nested.
* Beautiful is better than ugly.
* Simple is better than complex.
* Add blank line to the end of every file.
* Limit lines to 80 characters.


### JavaScript
* Two spaces indentation.
* Single quotes are preferred over double. Reason: HTML uses double quotes.
* Write code in functional style with minimum side effects.
* Don't use function statements. Instead, create anonymous functions and
assign them to consts for consistency with other consts.

    ```javascript
    // No
    function doThing(a, b) {return a * b;}

    // Yes
    const doThing = function(a, b) {return a * b;};
    ```

* Do not use quotes in object keys.

    ```javascript
    // No
    {'a': 'testtest'}

    // Yes
    {a: 'testtest'}
    ```

### HTML
* Two spaces indentation.

### CSS
* Two spaces indentation.
* Use lowercase hex colors (e.g. #fff) instead of color names (e.g. white).
* [Use `* {box-sizing: border-box;}`](http://paulirish.com/2012/box-sizing-border-box-ftw/).
* Use hyphens between class names, not camelCase or under_scores.
* Use only classes for styling most of the time (no #ids, elems etc).
* Don't use inline styling.
* Profile your selectors with webkit inspector.
* Use tree-style indentation.

    ```css
    .signup-page {
      background: #0d0; }
      .signup-button {
        padding: 10px;
        background-image: url("../img/signup.png"); }

    /* This looks cool if you use Stylus etc. */
    .chat-page {
      font-size: 0.9em; }
      .identity {
        margin-bottom: 20px; }
        .identity-profile {
          height: 4em; }
        .identity-nickname {
          float: left;
          width: 165px; }
        .identity-avatar {
          float: right; }
        .identity-updates {
          margin-top: 10px; }
        .identity-status {
          height: 30px; }
        .identity-current-mood {
          padding-left: 5px; }
        .identity-button {
          float: right; }
    ```

* Use this sequence of properties

    ```css
    .item {
      position: static;
      z-index: 0;
      top: 0;
      right: 0;
      bottom: 0;
      left: 0;

      display: block;
      visibility: hidden;
      float: none;
      clear: none;
      overflow: hidden;
      clip: rect(0 0 0 0);

      box-sizing: content-box;
      width: auto;
      min-width: 0;
      max-width: 0;
      height: auto;
      min-height: 0;
      max-height: 0;
      margin: 0;
      padding: 0;

      table-layout: fixed;
      empty-cells: show;
      border-spacing: 0;
      border-collapse: collapse;
      list-style: none;

      font: 1em sans-serif;
      font-family: Arial, sans-serif;
      font-size: 1em;
      font-weight: normal;
      font-style: normal;
      font-variant: normal;

      content: "";
      cursor: default;
      text-align: left;
      vertical-align: top;
      line-height: 1;
      white-space: normal;
      text-decoration: none;
      text-indent: 1;
      text-transform: uppercase;
      letter-spacing: 1;
      word-spacing: normal;

      opacity: 1;
      color: #d00;
      text-shadow: 5px 5px 5px #d59;
      border: 1px solid #d00;
      border-radius: 15px;
      box-shadow: inset 1px 0 0 #fff;
      background: #fff url("../i/bg.png") no-repeat 0 0; }
    ```


    
# Tech/ Framework Used

**We used *MERN Stack* framework to create this Web Application**. MERN stack is a software stack that includes four open-source technologies: (MongoDB, Express.js, React, and Node.js). These components provide an end-to-end framework for building dynamic websites and web applications.



##### Database 
* [Mongo DB](https://www.mongodb.com/) - The only database that harnesses the innovations of NoSQL. MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas. MongoDB is developed by MongoDB Inc. and licensed under the Server Side Public License.

* [Firebase Storage](https://console.firebase.google.com/) - as a cloud storage for files.

##### Node.js Framework
* [Express JS](http://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js.Express.js, or simply Express, is a back end web application framework for Node.js that is released as free and open-source software under the MIT License. It is designed for building web applications and APIs. It has been called the de facto standard server framework for Node.js.

##### Frontend
* [React JS](https://reactjs.org/) - A declarative, efficient, and flexible JavaScript library for building user interfaces.React is a free and open-source front-end JavaScript library for building user interfaces based on UI components. It is maintained by Meta and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

##### Backend
* [Node JS](http://nodejs.org/) - A platform built on Chrome's JS runtime for easily building fast, scalable network apps. Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.

#### other used technologies 
The used packages and technologies with-in the app:
    Mongoose as a DB handler package for node and react.
    Tailwind css as a css-provider for the app.
    React-Redux as a state manager for the app.
    ZegoCloud as a video provider.
    Js-PDF as a package for handling PDF files in the app.
    React-Image-Gallery as a picture handler.
    Node mailer as a mailing service.
    Stripe as a Payment Handler.
    Otp-generator for OTP services.
    Json-web-token for handling authentications.
    Express.js for handling APIs.
    CORS for handling network.
    DOTENV for handling .env files.
    bcryptjs for hashing passwords,
    firebase-admin for sending notification via firebase from backend,
    nodemailer for sending mails,
    otp-generator for generating otps and verify,


# Required Installations
### [Visual Studio Code](https://code.visualstudio.com/download)
### [Node](https://nodejs.org/en/download/)
### Libraries & Framework
All commands needed to install all required libraries and frameworks can be found at [npm website](https://www.npmjs.com/).
//TODO : edit references
# API References
#### [Stripe API](https://stripe.com/docs/api)
We are planning onto using this api in order to test paying with credit cards on our website.

# Tests
We usually tested our backend using [Postman](https://www.postman.com/downloads/), and we tested our frontend by running it using the command *npm start* in the frontend using the command line. It is also good to know that backend functionality can be tested using jtests, yet we prefered using the other methods mentioned above.


curl --location 'http://localhost:3002/Admin/createAdmin' \
--header 'Content-Type: application/json' \
--data '{
    "userName": "",
    "password": "",
    "email": ""
}'

# API Referencs      
This is a navigation map to the app
        # post:
            /cart/addItem
            /admin/addAdmin
            /admin/pharmacistActivation
            /pay/checkout-stripe
            /pay/checkoutByWallet
            /pay/onDelivery
            /patient/createPatient
            /patient/createAddress
            /medicine
            /pharmacist/addPharmacist
            /auth/login
            /auth/resetPassword
            /auth/changePassword
            /otp/send
            /otp/verify

        # put:
            /cart/removeItem
            /cart/reduceItem
            /cart/increaseItem
            /order/updateStatus
            /order/cancel
            /patient/updateWallet
            /medicine/setArchive
            /medicine

        # get:
            /cart/getCart
            /admin/pendingRequests
            /order/getPatientOrder
            /patient/
            /patient/getPatient
            /patient/getPatientAddresses
            /medicine
            /medicine/getMedicinesByName
            /medicine/getAlternativeMedicines
            /pharmacist/getPharmacist
            /pharmacist/
            /pharmacist/salesReports

        # delete:
            patient/:id
            /medicine/:id
            /pharmacist/:id 


# code examples
### create admin
const createAdmin = async (req, res) => {

  const salt = await bcrypt.genSalt(10);
  var encryptedPassword = await bcrypt.hash(req.body.password, salt);
  req.body.password = encryptedPassword;

  try {
    const savedAdmin = await AdminssModel.create(req.body);
    res.status(200).json({
      data:savedAdmin,
      success:true
    });

    
  } catch (error) {
    console.error("Error creating patient:", error);
    res.status(500).json({ error: "Failed to create a new Patient" });
  }

};

### update order
const updateOrderStatus = async (req, res) => {
  try {
    const orderId = req.body.orderId;
    const newStatus = req.body.newStatus;

    const order = await OrdersModel.findOne({_id:orderId});

    if (!order) {
      return res.status(404).json({ message: "Order not found" });
    }
    order.status = newStatus;
    order.save().then(async resp=>
      {
        var cart = await CartModel.findOne({user:order.user});
        for await (var med of cart.medicines){
          var medicine = await MedicineModel.findOne({_id:med.medicine})
          medicine.quantity = medicine.quantity - med.quantity;
          medicine.sales = medicine.sales + med.quantity;
          medicine.save();
          const salesReport = await SalesReportModel.create({
            medicine,
            order,
            quantityInStock:medicine.quantity,
            salesQuantity:med.quantity,
            salesPrice:medicine.price * med.quantity
          })
        }
        const {medicines, user, totalPrice } = cart;

        var pCart = await PurchasedCartModel.create({medicines, user, totalPrice, status:"completed", orderId:order._id })
        await CartModel.deleteOne({_id:cart._id})
      return res.status(200).json({success:true, data:{order}})
    })
    
    console.log("updated Order");
  } catch (error) {
    console.error(error);
    res.status(500).json({ message: "Server error while updating" });
  }
};

### increaseItemInCart
  const increaseItemInCart = async (req,res)=>{
    const { medicineId, patientId } = req.query;

  var patient = await PatientsModel.findOne(
    { _id: patientId },
    { password: 0, __v: 0 }
  );
  if (patient) {
    var cart = await CartModel.findOne({ user: patientId });
    var medicine = await MedicineModel.findOne({ _id: medicineId });
    if (medicine === null || medicine?.quantity <= 0 ) {
      return res.status(404).json({
        success: false,
        data: { message: "medicine out of stock" }
      });
    }
    cart.medicines = cart.medicines?.map(c => {
        if (c.medicine.equals(medicine._id)) {
            c.quantity += 1;
            cart.totalPrice += medicine.price;
        }
        return c;
    });
    cart.medicines = cart.medicines.filter(c=> c.quantity  !== 0);
    cart.save().then(resp=>
        res.status(201).json({
            success: true,
            data: cart 
          })
        )
  }else{
    return res.status(404).json({
        success: false,
        data: { message: "patient not exist" }
      });
  }
}  


# Screenshots 
### pharmacist account : https://github.com/advanced-computer-lab-2023/Whatthescrum-Pharmacy/blob/0d192cb1d742f83b825c083e8b15480e3e6fcbf1/pharmacist%20home%20page.png
### patient account : https://github.com/advanced-computer-lab-2023/Whatthescrum-Pharmacy/blob/0d192cb1d742f83b825c083e8b15480e3e6fcbf1/patient%20account%20in%20pharmacy.png
### medicines in pharmacist account : https://github.com/advanced-computer-lab-2023/Whatthescrum-Pharmacy/blob/0d192cb1d742f83b825c083e8b15480e3e6fcbf1/medicines%20in%20pharmacist%20account.png


# Features : 
  patient : 
    view doctors , select a certain appointment , filter doctors and appointments , view presctiptions , purchase a prescription , chat with doctor and pharmacist, add address , view cart and edit cart 

 pharmacist : 
    create medicine, archive and unarchive a medicine , chat with docotr and patient , check sales report. 

# Required Installations
### [Visual Studio Code](https://code.visualstudio.com/download)
### [Node](https://nodejs.org/en/download/)
### Libraries & Framework
All commands needed to install all required libraries and frameworks can be found at [npm website](https://www.npmjs.com/).

# Contribute
Any contributions are highly appreciated as this is our first MERN Stack application, and we would love to learn and develop more.

# Credits
Special credits go to **CSEN704 Advanced Computer Lab Course Team**: *Assoc. Prof. Mervat Abuelkheir, Eng. Noha Hamid, Eng. Nada Ibrahim , Eng. Fatma Hosam , Eng. Amr Diab, Eng. Mabrook and Eng. Hadwa Pasha* at the Faculty of Media Engineering and Technology in The German University in Cairo. We, also, want to thank [**The Net Ninja**](https://www.youtube.com/@NetNinja) Youtube channel as we obtained a lot of information from its playlist [MERN Stack Crash Course Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iJ_KkrkBZWZRHVwnzLIoUE).



# License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)(https://stripe.com/docs/api) (www.zegoCloud.com)
