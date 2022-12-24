# reactFromZero

This repo is created for understanding react from zero you will see here the stuff like
  CDN for react,
  Creating react element using React.createElement("tag name/component Name", {"This will include props","what this tag will contain"}
  Createing root element using ReactDOM.createRoot("RootId")
  Appending child to root using root.render(element)
  
  
  
  
  Creating multiple child using React.createElement()
  
    const firstName = React.createElement("h1",{id:firstName},"Abhinandan");
    const lastName =  React.createElement("h1",{id:lastName},"Shah");
    const root = ReactDOM.createRoot("root");
    root.render([firstName,lastName]);
    
   
