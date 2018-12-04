### Creating a new CXL Element

1. Clone this repo

        git clone git@github.com:conversionxl/cxl-element-skeleton.git cxl-new-element-name

2. When in the `cxl-new-element-name` folder, replace all `cxl-element` and `CXLElement` occurrences with your new element name.

        perl -pi -e 's,cxl-element,cxl-new-element-name,g' *.* demo/* test/* src/* theme/*/*
        perl -pi -e 's,CXLElement,CXLNewElementName,g' *.* demo/* test/* src/* theme/*/*

3. Rename the element

        mv cxl-element.html cxl-new-element-name.html
        mv src/cxl-element.html src/cxl-new-element-name.html
        mv theme/lumo/cxl-element.html theme/lumo/cxl-new-element-name.html
        mv theme/material/cxl-element.html theme/material/cxl-new-element-name.html

4. Check that everything works all right

        npm install
        bower install
        polymer serve

  And check that everything works:

  - http://localhost:8080/components/cxl-new-element-name/index.html
  - http://localhost:8080/components/cxl-new-element-name/demo/index.html
  - http://localhost:8080/components/cxl-new-element-name/test/index.html

5. Remove this README file since it is not needed any more.

        rm README_CREATE_NEW.md
