npx create-react-app react-admin
cd .\react-admin\
code .

install below libs
npm i @mui/material @emotion/react @emotion/styled @mui/x-data-grid @mui/icons-material react-router-dom@6 react-pro-sidebar formik yup @fullcalendar/core @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/list @nivo/core @nivo/pie @nivo/line @nivo/bar @nivo/geo

delete below files 

react-admin/src/setupTests.js 
react-admin/src/reportWebVitals.js 
react-admin/src/logo.svg 
react-admin/src/App.test.js 
react-admin/src/App.css


Note: follow ducks pattern to organise code 

/components to components which are used in multiple locations 
/scenes for each pages
/global for top bar