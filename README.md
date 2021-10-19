# HTML-CSS-Coding-Standard
The main goal is to write well-structured and standards-compliant markup.

# Principles of Standardized Code

   1. Code should be readable and understandable by all members of the team. This includes internal and external developers.
   
   2. All code, regardless of the project, should read as if it was developed by a  single person regardless of how many individuals actually worked on it.
   
   3. The style of writing and implementation of these Code Standards is agreed upon and implemented by the team.
   
   4. Assist in developing well-formed, semantically correct, and mostly valid code.
   
   5. Aid in the onboarding of new development team members to new and existing projects.

      # Code Re-usability:

      Code which shares a very similar or identical structure should be written in such a way that it can be used further.
      
      # Code Check:
      
      Before submitting the code it should be reviewed and checked properly maintaining the above guidelines rules.

# HTML coding standards
  
  # Formatting
     
     All HTML documents must use two spaces for indentation and there should be no trailing whitespace. HTML5 syntax must be used and all attributes must use double quotes            around attributes.
      
  # Doctype and layout
  
    All documents must be using the HTML5 doctype and the <html> element should have a "lang" attribute. The <head> should also at a minimum include "viewport" and "charset"         meta tags.
    
  # Including meta data
  
    Classes should ideally only be used as styling hooks. If you need to include additional data in the HTML document, for example to pass data to JavaScript, then the HTML5         data- attributes should be used.
    
  # Forms
  
    Form fields must always include a <label> element with a "for" attribute matching the "id" on the input. This helps accessibility by focusing the input when the label is         clicked, it also helps screen readers match labels to their respective inputs.
    Each <input> should have an "id" that is unique to the page. It does not have to match the "name" attribute.
    Forms should take advantage of the new HTML5 input types where they make sense to do so, placeholder attributes should also be included where relevant. Including these can       provided enhancements in browsers that support them such as tailored inputs and keyboards.
    
  # i18n
  
    Don’t include line breaks within <p> blocks. 
    ie do this:
    <p>Blah foo blah</p>
    <p>New paragraph, blah</p>
    
    And not:
    
    <p>Blah foo blah
    New paragraph, blah</p>
    
  
  
