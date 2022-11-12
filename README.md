


# Readings: Chakra UI

Below you will find some reading material, code samples, and some additional resources that support today's topic and the upcoming lecture.

## Review, Research, and Discussion

In your reading notes page for this class, provide answers to the following prompts. Cite any external sources

-   What is a Chakra UI?
### Chakra UI is a simple, modular and accessible component library that gives you the building blocks you need to build your React applications.
-   Is Chakra UI better than material UI?
### Chakra UI is a more robust, layout-focused library that offers developers UI components similar to those provided by Material UI, but with a greater emphasis on the creation of flexible, composable, and scalable code. When comparing the two frameworks, one key concept to consider is 'Ease of Modification.'
-   How to use Chakra UI?
1.  npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion.
2.  yarn add @chakra-ui/react @emotion/react @emotion/styled framer-motion.
3.  pnpm add @chakra-ui/react @emotion/react @emotion/styled framer-motion.
 *After installing Chakra UI, you need to set up the  `ChakraProvider`  at the root of your application. This can be either in your  `index.jsx`,  `index.tsx`  or  `App.jsx`  depending on the framework you use.*
```
import * as React from 'react' 
import * as React from 'react' 
// 1. import `ChakraProvider` component import
{ ChakraProvider } from '@chakra-ui/react' 
function App() 
{ 
// 2. Wrap ChakraProvider at the root of your app 
return
 ( 
 <ChakraProvider>
 <TheRestOfYourApplication />
 </ChakraProvider> ) 
 }
```

## Preparation Materials

[https://chakra-ui.com/](https://chakra-ui.com/)
