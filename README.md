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
