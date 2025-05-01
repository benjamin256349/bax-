<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Color Change Example</title>

    <style>
        .my-div-with-plain-css {
            background-color: #f0f0f0; /* Light grey background */
            color: #333333;           /* Dark grey text */
            padding: 20px;            /* Add some space inside */
            margin-bottom: 20px;      /* Add space below */
            border: 1px solid #cccccc;/* Add a light border */
        }

        .my-heading-with-plain-css {
            color: #0056b3; /* A blue color for the heading */
        }
    </style>

    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* You can still mix custom CSS with Tailwind */
        .my-div-with-tailwind {
             /* Tailwind classes handle the styling */
        }
    </style>

</head>
<body class="font-sans p-8">

    <h1 class="text-2xl font-bold mb-4">How to Change Colors</h1>

    <div class="my-div-with-plain-css">
        <h2 class="my-heading-with-plain-css">This is styled with Plain CSS</h2>
        <p>The background color of this box is light grey, and the text color is dark grey. The heading text is blue.</p>
    </div>

    <div class="bg-blue-200 text-blue-800 p-4 mb-4 border border-blue-400">
        <h2 class="text-blue-900 font-semibold">This is styled with Tailwind CSS</h2>
        <p>The background color of this box is light blue, and the text color is dark blue. The heading text is even darker blue.</p>
    </div>

    <div class="bg-green-800 text-stone-200 p-4 mb-4 rounded shadow-md">
         <h2 class="text-stone-100 font-semibold">Using Your Palette with Tailwind</h2>
         <p>This box uses your forest green background and a light beige text color, similar to your landing page header.</p>
    </div>


</body>
</html>
