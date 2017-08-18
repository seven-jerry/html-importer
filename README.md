# html importer
 this script imports files ( js,css ) into a html document
 import js file to html
 import css file to html


 before:

    <html>
        <head>
        <!-- {SVN_AUTO_IMPORT type:.js; dir:js; exclude:; template:<script src="%PATH"</script>;} -->
        </head>
        
after:

    <html>
       <head>
         <script src="../tsc_out/script1.js"></script>
        <script src="../tsc_out/script2.js"></script>
        <script src="../tsc_out/script3.js"></script>
        <script src="../tsc_out/script4.js"></script>
        <script src="../tsc_out/script5.js"></script>
      </head>
