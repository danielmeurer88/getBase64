# getBase64
transforms a file into its base 64 representation

## How can this be useful?

You can add images to your css rules. This can improve the speed of your website or allow you the use of images, if you are restricted to plain text files (as it is the case for many seed projects)

 - generate your base 64 file
 - copy the text
 - and paste it between the brackets of the url()-value
 
 ### Examples
 
 .css-picture {
      background-image : url(<paste-yourBase64-here>);
 }
 
.css-heart {
      background-image : url(data:image/jpeg;base64,/9j/4AAQSkZJRgABAgEASABIAAD//gAmUGFpbnQgVG9vbCAtU0FJLSBKUEVHIEVuY29kZXIgdjEuMDAA/9sAhAABAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQYEBAQEBAYGBgYICAgICAsLCwsLCw0NDQ0NDQ0QEBAQEBAQEBQUFBQUFBQYGBgYGBgcHBwcHCAgICAlJSUqKiz/wAARCAAKAAoDAREAAhEBAxEB/8QBogAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoLEAACAQMDAgQDBQUEBAAAAX0BAgMABBEFEiExQQYTUWEHInEUMoGRoQgjQrHBFVLR8CQzYnKCCQoWFxgZGiUmJygpKjQ1Njc4OTpDREVGR0hJSlNUVVZXWFlaY2RlZmdoaWpzdHV2d3h5eoOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4eLj5OXm5+jp6vHy8/T19vf4+foBAAMBAQEBAQEBAQEAAAAAAAABAgMEBQYHCAkKCxEAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwD6a/bH/bx/4LI/ssftrfHr9n2x1rX9cuPj54i1LT/2atJtfBGleKobbwZq/jFl+Huv/A+1sNPkgk8QwaFbt4S1aw1S315oby51CfxRpt14ksrHVrfxMTi8zw+KqU7t8793Tp5H2GXZXw9jstoV2kvZL9571tba8x/R58Jfhr/wUJm+FXwym+I/7QOj6b8Q5fh94Ml8eaddeDPAV9dWHjOTw3preKLK5vdG8PPpF5Pa64b6Ca60p2024kjaaxZrV4ifSp08Z7OPNUXNyq+i3Pn69bKVXqezoNw53y6va+h+h9xo2j3mo6ZrF3pWmXWr6Ml4mj6pcWNrPqOlJqUUcOoppl9LE1zYpfwxRRXi2ssQuoo445xIqKB0WTadtjgUpKLSbs9zTpiP/9k=);
 
this is the base64-code of 10x10px heart ... so be ready for some long code when the picture is bigger
