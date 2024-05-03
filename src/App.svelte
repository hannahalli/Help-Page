<!-- App.svelte -->
<script>

</script>

<div class="container">
    <h2>Help Guide</h2>
    <div class = "paragraph-container">
        <p><strong>Closing Windows:</strong> Click the close button to return to the beanstalk.</p>
        <p><strong>Navigation:</strong> Use the red sign to go back to the main window.</p>
        <p><strong>Fairy Visits:</strong> Keep an eye out! The fairy arrives every 10 minutes.</p>
        <p><strong>Feedback:</strong> Have ideas or encountered a problem? Fill out the Google Form!</p>
        <p><strong>Urgent Fixes:</strong> Need immediate help? Contact hannahballison@gmail.com.</p>
        
    </div>
    
    <p>Enjoy embarking on a magical journey!</p>
</div>

<style>
    /* Add your CSS styles here */
    .container {
        position: absolute;
        top: 65px; /* Adjust the top position as per your requirement */
        left: calc((1536px - 500px) / 2 + 250px); /* Adjust the left position as per your requirement */
        width: 270px; /* Increase width */
        height: 550px; /* Increase height */
        background-color: #FAEBD7; /* Set light brown background color */
        border: 16px solid #63310e; /* Set dark brown border */
        padding: 20px;
        border-radius: 5px;
        /* overflow-y: auto; Enable scrolling if content overflows */
        z-index: 1; /* Ensure the container is above other elements */
        pointer-events: auto; /* Enable pointer events for the container */
        text-align: center; /* Center text horizontally */
        color: #8B4513; /* Set text color to dark brown */
        font-family: Chalkboard, sans-serif; /* Set font to Chalkduster */
    }

    h2 {
        margin-top: 0px; /* Lower the margin top */
        font-size: 40px;
    }

    .paragraph-container {
        background-color: #e3fad7; /* Set light brown background color */
        padding: 10px; /* Add padding */
        border-radius: 10px; /* Add border radius */
        margin-bottom: 5px; /* Add margin bottom */
        margin-top: -10px;
        width: 230px; /* Set width to auto */
        align-items: center;
        border: 5px solid #8B4513; /* Set dark brown border */
        margin-left: 0px;
    }

    p {
        font-size: 16px; /* Set font size for paragraphs */
    }
</style>

