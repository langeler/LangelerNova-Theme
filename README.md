# SCSS Directory Structure

```plaintext
scss/
│
├── colors/
│   ├── _core-colors.scss                    // Core color definitions used across all sections
│   │
│   ├── interface/
│   │   ├── _base-colors.scss                // Colors for base interface elements (window, titlebar, etc.)
│   │   ├── _button-colors.scss              // Colors for buttons
│   │   ├── _textfield-colors.scss           // Colors for textfields
│   │   ├── _document-colors.scss            // Colors for document (editor)
│   │   ├── _gutter-colors.scss              // Colors for gutter (line numbers, etc.)
│   │
│   ├── terminal/
│   │   ├── _terminal-colors.scss            // Colors for terminal elements (ANSI colors)
│   │
│   ├── syntax/
│   │   ├── _keywords-colors.scss            // Colors for syntax keywords
│   │   ├── _comments-colors.scss            // Colors for syntax comments
│   │   ├── _processing-colors.scss          // Colors for processing directives
│   │   ├── _declarations-colors.scss        // Colors for declarations
│   │   ├── _brackets-colors.scss            // Colors for brackets
│   │   ├── _operators-colors.scss           // Colors for operators
│   │   ├── _invalid-colors.scss             // Colors for invalid syntax
│   │   ├── _values-colors.scss              // Colors for values (numbers, booleans, etc.)
│   │   ├── _strings-colors.scss             // Colors for strings
│   │   ├── _regex-colors.scss               // Colors for regex
│   │   ├── _cdata-colors.scss               // Colors for CDATA sections
│   │   ├── _identifiers-colors.scss         // Colors for identifiers (variables, functions, etc.)
│   │   ├── _definitions-colors.scss         // Colors for definitions (classes, functions, etc.)
│   │   ├── _tags-colors.scss                // Colors for markup tags (HTML, XML)
│   │   ├── _stylesheets-colors.scss         // Colors for stylesheet elements (CSS selectors, properties)
│   │   ├── _markup-colors.scss              // Colors for markup (non-tag elements)
│   │
│   ├── languages/
│   │   ├── advphp/
│   │       ├── _comments-colors.scss        // Colors for Advanced PHP comments
│   │       ├── _statics-colors.scss         // Colors for Advanced PHP statics
│   │       ├── _wordpress-colors.scss       // Colors for WordPress keywords
│   │       ├── _curl-colors.scss            // Colors for cURL keywords
│   │       ├── _sql-colors.scss             // Colors for SQL keywords
│   │       ├── _syntax-colors.scss          // Colors for Advanced PHP syntax
│   │       ├── _variables-colors.scss       // Colors for Advanced PHP variables
│   │       ├── _functions-colors.scss       // Colors for Advanced PHP functions
│   │       ├── _objects-colors.scss         // Colors for Advanced PHP objects
│   │       ├── _namespace-colors.scss       // Colors for Advanced PHP namespaces
│   │       ├── _strings-colors.scss         // Colors for Advanced PHP strings
│   │       ├── _control-structures-colors.scss // Colors for control structures (if, else, etc.)
│   │       ├── _error-handling-colors.scss  // Colors for error handling (try, catch, throw)
│   │       ├── _magic-constants-colors.scss // Colors for magic constants (e.g., __CLASS__)
│   │       ├── _keywords-colors.scss        // Colors for Advanced PHP keywords
│   │       ├── _additional-elements-colors.scss // Colors for additional PHP elements
│
├── sections/
│   ├── interface/
│   │   ├── _base.scss                       // Styles for base interface elements (window, titlebar, etc.)
│   │   ├── _buttons.scss                    // Styles for buttons
│   │   ├── _textfields.scss                 // Styles for textfields
│   │   ├── _document.scss                   // Styles for document-related elements (editor)
│   │   ├── _gutter.scss                     // Styles for gutter elements (line numbers, etc.)
│   │
│   ├── terminal/
│   │   ├── _terminal.scss                   // Styles for terminal elements using ANSI color codes
│   │
│   ├── syntax/
│   │   ├── _keywords.scss                   // Styles for syntax keywords
│   │   ├── _comments.scss                   // Styles for syntax comments
│   │   ├── _processing.scss                 // Styles for processing directives
│   │   ├── _declarations.scss               // Styles for declarations
│   │   ├── _brackets.scss                   // Styles for brackets
│   │   ├── _operators.scss                  // Styles for operators
│   │   ├── _invalid.scss                    // Styles for invalid syntax
│   │   ├── _values.scss                     // Styles for values (numbers, booleans, etc.)
│   │   ├── _strings.scss                    // Styles for strings
│   │   ├── _regex.scss                      // Styles for regex
│   │   ├── _cdata.scss                      // Styles for CDATA sections
│   │   ├── _identifiers.scss                // Styles for identifiers (variables, functions, etc.)
│   │   ├── _definitions.scss                // Styles for definitions (classes, functions, etc.)
│   │   ├── _tags.scss                       // Styles for markup tags (HTML, XML)
│   │   ├── _stylesheets.scss                // Styles for stylesheet elements (CSS selectors, properties)
│   │   ├── _markup.scss                     // Styles for markup (non-tag elements)
│   │
│   ├── languages/
│   │   ├── advphp/
│   │       ├── _comments.scss               // Styles for Advanced PHP comments
│   │       ├── _statics.scss                // Styles for Advanced PHP statics
│   │       ├── _wordpress.scss              // Styles for WordPress keywords
│   │       ├── _curl.scss                   // Styles for cURL keywords
│   │       ├── _sql.scss                    // Styles for SQL keywords
│   │       ├── _syntax.scss                 // Styles for Advanced PHP syntax
│   │       ├── _variables.scss              // Styles for Advanced PHP variables
│   │       ├── _functions.scss              // Styles for Advanced PHP functions
│   │       ├── _objects.scss                // Styles for Advanced PHP objects
│   │       ├── _namespace.scss              // Styles for Advanced PHP namespaces
│   │       ├── _strings.scss                // Styles for Advanced PHP strings
│   │       ├── _control-structures.scss     // Styles for control structures (if, else, etc.)
│   │       ├── _error-handling.scss         // Styles for error handling (try, catch, throw)
│   │       ├── _magic-constants.scss        // Styles for magic constants (e.g., __CLASS__)
│   │       ├── _keywords.scss               // Styles for Advanced PHP keywords
│   │       ├── _additional-elements.scss    // Styles for additional PHP elements
│
├── main.scss                                // Main SCSS file that imports all the other SCSS files
Explanation of the Structure

	•	colors/ Directory:
	•	Contains all the color variables organized by core colors, interface elements, terminal elements, syntax highlighting, and language-specific (Advanced PHP) elements.
	•	sections/ Directory:
	•	Contains the styling rules organized by interface elements, terminal elements, syntax elements, and language-specific elements (Advanced PHP).
	•	main.scss:
	•	The entry point SCSS file that imports all the other SCSS files to compile the final theme.
