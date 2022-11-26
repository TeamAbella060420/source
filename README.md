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

<div style={{display: 'flex', justifyContent: 'center'}}>
  <Popover> 
    <div
      style={{
        width: 120,
        whiteSpace: 'nowrap',
        textOverflow: 'ellipsis',
        overflow: 'hidden'
      }}
    <div/>
      onClick={(e) => {
        e.stopPropagation();
       this.getDetail(data);
      }}
    >
    {text}
    <div/>
  <Popover/>
<div/>

//10 React JS Practice Exercises with solution

https://contactmentor.com/react-js-practice-exercises-solution/

// Codesandbox counter

https://upmostly.com/tutorials/build-a-react-timer-component-using-hooks

// CSS Solution 1
// Flex

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    height: 100vh;
}

.parent {
    background: yellow;
    height: 100%;
    width: 100vw;
    display: flex;
    padding: 20px;
}

.blue {
    background: blue;
    flex: 1;
    height: 100%;
}

.red {
    background: red;
    height: 100%;
    width: 200px;
}

// CSS Solution 2
// Position Relative

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    height: 100vh;
}

.parent {
    background-color: yellow;
    height: 100%;
    width: 100%;
    position: relative;
    padding: 20px;
 }
 
 .red {
    background-color: red;
    width: 200px
    height: 100%;
    position: relative;
    z-index: 10;
  }
  
  .blue {
    background-color blue;
    width: calc(100% - 200px);
    position: absolute;
    inset: 20px 20px 20px auto;
  }


// CSS Solution 3
// Float

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    height: 100vh;
}

.parent {
    background-color: yellow;
    height: 100%;
    position: relative;
    padding: 20px;
 }
 
 .red {
    background-color: red;
    width: 200px;
    height: 100%;
    float: left;
  }
  
  .blue {
    background-color: blue;
    width: calc(100% - 200px);
    height: 100%;
    float: right;
  }
    
// CSS Solution 4
// Grid
    
 * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    height: 100vh;
}  
    
 .parent {
    background-color: yellow;
    height: 100%;
    padding: 20px;
    display: grid;
    grid-template-columns: 200px 1fr;
    padding: 20px;
 }
 
 .red {
    background-color: red;
    height: 100%;
  }
  
  .blue {
    background-color: blue;
    height: 100%;
  }
   
// Three button AddEventListener
    
    window.tool = new Tool
    const genggeng = window.tool
    
   document.getElemntById("one1").addEventListener("click", () => {
      genggeng.one()
      genggeng.one()
      genggeng.two()
      genggeng.one()
    });

