Version 1.6.3  - Under development
  - Feature #11: Support HTML5 Self-Closing Tag Syntax
  - Integrate jQuery UI 1.14.2, jQuery 4.0.0, jQuery Chosen 3.0.0

Version 1.6.2  - Jul 2025
  - Fix #10: Install files with gprinstall

Version 1.6.1  - Sep 2024
  - Cleanup build environment to drop configure

Version 1.6.0   - Aug 2023
  - Improvement of <f:viewParam> to accept a from EL expression to setup the value
  - Add util:parseJSON() EL function
  - Integrate jQuery UI 1.13.2, jQuery 3.7.0, jQuery Chosen 2.2.1, jQuery Datetime picker 2.5.22
  - Fix #4: Support to build with -gnatW8
  - Feature #2: Upgrade dropzone to 6.0

Version 1.5.0   - Aug 2022
  - New widget <w:progress> to display horizontal/vertical progress bars

Version 1.4.3   - Jul 2021
  - Add jQuery 3.6.0
  - Add a programmer's guide
  - Remove very old jQuery 1.11.3, jQuery UI 1.11.4, jQuery Chosen 1.4.2

Version 1.4.2   - Feb 2021
  - Fix compilation warnings
  - Cleanup build and examples

Version 1.4.1   - Nov 2020
  - Fix translations, compilation warnings

Version 1.4.0   - May 2020
  - Performance improvement for the Facelet cache
  - Integrate jQuery 3.4.1, jQuery UI 1.12.1, jQuery Chosen 1.8.7
  - New <f:validateRegex> to validate an input field with a regular expression

Version 1.3     - Dec 2019
  - New converter to format floating point numbers
  - Improvement of the build environment

Version 1.2     - Jul 2018
  - New EL function util:translate for translation with a resource bundle
  - New REST servlet with support for server API implementation
  - Provide pre-defined beans in ASF contexts: requestScope
  - Add support for servlet requests to retrieve the body content as a stream
  - Improvement of navigation rules to allow setting the return status
  - Moved the servlet support in a separate project: ada-servlet
  - Integrate jQuery datetime picker

Version 1.1     - Dec 2015
  - New EL function util:formatDate
  - New request route mapping with support for URL component extraction and parameter
    injection in Ada beans
  - Improvement of configure, build and installation with gprinstall when available
  - Integrate jQuery 1.11.3 and jQuery UI 1.11.4
  - Integrate jQuery Chosen 1.4.2
  - New component <w:chosen> for the Chosen support
  - Added a servlet cache control filter

Version 1.0.1   - Jul 2014
  - Fix minor configuration issue with GNAT 2014
  - Fix concurrent issues in facelet and session cache implementation

Version 1.0     - Apr 2014
  - Add support for Facebook and Google+ login
  - Javascript support for popup and editable fields
  - Added support to enable/disable mouseover effect in lists
  - New EL function util:iso8601
  - New component <w:autocomplete> for input text with autocompletion
  - New component <w:gravatar> to render a gravatar image
  - New component <w:like> to render a Facebook, Twitter or Google+ like button
  - New component <w:panel> to provide collapsible div panels
  - New components <w:tabView> and <w:tab> for tabs display
