# source

.button:hover {
box-shadow: 0 1px 20px 0 rgb(60 142 254 / 20%)
}

// For animation packages

npm i framer-motion

export const routeAnimation = {
  initial: {
     opacity: 0,
  },
  animate: {
    opacity: 1,
    transition: {
      delay: 0.1,
      duration: 0.1,
    },
  },
  exit: {
    opacity: 0,
    transition: {
      delay: 0.1,
      ease: 'easeInout'
    }
  }  
}


<motion.div variants={routeAnimation} initial="initial" animate="animate" exit="exit">

// @ _app.tsx

<AnimatePresence exitBeforeEnter>
  <Component {...pageProps} key={routes.route}/>
</AnimatePresence>  

// Hover image

.hover-scale:hover {
  transform: scale(1.1);
  transition-delay: 100ms;
  transition-duration: 500ms;
}

// Scroll bar design

::webkit-scrollbar-thumb {
  background-image: linear-gradient(to right bottom, #00f260, #055e6)
}

::-webkit-scrollbar {
  width: 8px;
  height: 0px;
}

// Portfolio url

https://six-digits-pink.vercel.app/

// Updated the projects

https://six-digits-pink.vercel.app/

// Deployment Website

https://vercel.com/dashboard

// Saving Data's in local storage

const myJSON = JSON.stringify(filterChecked);
localStorage.setItem("filteredList", myJSON);
const returnJSON = localStorage.getItem("filteredList");
let parseJSON = JSON.parse(returnJSON);

// Limiting the remarks text on the width
style = {{
  width: '60px',
  overFlow: 'hidden',
  textOverflow: 'ellipsis',
  marginLeft: '15px'
}}

// Current date on the calendar
current < moment().days()moment().days() - 90).satartOf('days') || current > moment().endOf('days')

//Show modal wraped in a constant width adding triple ... at the end

<div>
  <Popover> 
    <div>
      style={{
        width: 120,
        whiteSpace: 'nowrap',
        textOverflow: 'ellipsis',
      }}
    <div/>
  <Popover/>
<div/>
