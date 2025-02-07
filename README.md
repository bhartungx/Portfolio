
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> My Portfolio </title> <!-- Add the title inside the <title> tags -->
    <style>
        /* Adding some simple styles */
        #projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 20px;
        }
        .project {
            margin: 20px;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
        }
        /* Here’s the code that makes your image smaller and adds a border */
        .project img {
            width: 50%; /* Image takes up all available space */
            max-width: 300px; /* Limit size to 300px wide */
            height: auto; /* Keeps the image shape right */
            border: 5px solid #333; /* Solid black border around image */
            border-radius: 8px; /* Rounded corners for the border */
        }
        /* Caption styling */
        .caption {
            padding: 10px;
            background-color: #fff;
            color: #333;
        }
        .caption h3 {
            font-size: 1.2rem;
            margin: 10px 0;
        }
        .caption p {
            font-size: 1rem;
            color: #666;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bridget Hartung</h1>
        <p>Welcome to my portfolio! Here you can see some work samples created within the last 8 months. Thanks for taking a look-I hope you enjoy! </p>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <p>I'm an early career environmental scientist with a focus on GIS. I received my Bachelor's of Science from USF with 2 minors, GIS and Spanish. I have 2 years of experience with ArcGIS Pro, and enjoy creating maps about local environmental issues. My goal is to work in environmental consulting and assist in implementation of and compliance with sustainable policies, design, and resource management. Eventually I wish to work in resource management and sustainability, leveraging my environmental experience with my passion for education to improve understanding of environmental processes to adults and youth. I'm proficient in Spanish and have successfully taught English to Spanish speakers at a community library program and as well as traveled in Spanish speaking countries. I'm passionate about education on all levels, and tutor in my free time.</p>
    </section>
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
        <a href="https://github.com/bhartungx/Portfolio/blob/main/brownfield_paper.jpg" target             
        "https://github.com/bhartungx/Portfolio/blob/main/brownfield_paper.jpg">
            <img src="https://github.com/bhartungx/Portfolio/blob/main/brownfield_paper.jpg" alt="Project 1">
         <div class="caption">
                 <h3>Project 1</h3>
                <p>Every year, an estimated 30-40% of food in the US goes in the trash. This amounts to around 60 million TONS per year. This map shows my local area, Pinellas and Hillsborough counties, and their food waste in tons. There are several composting programs, and this map details the net food waste, excluding waste that is composted.
Especially in Pinellas County, landfill space is scare. 80% of waste is incinerated and used to power homes. However, the remaining waste is exported to a landfill that is expected to fill within 80 years, with no potential new landfill locations to be found.
Throughout this spatial analysis, I measured the tons of non-composted food waste per zip code in my local area, encompassing Pinellas and Hillsborough Counties in Florida. I found that on average, 3746 tons of food waste per zip code went straight into the landfill. This figure is inferred to be annual as given in "per capita" metrics, although not explicitly mentioned by the data source (EPA, 2023). Depending on the zip code, anywhere from 1-12,000 tons of food waste went into the landfill.
There are many greener measures that can be taken, such as rerouting or repurposing waste, and decreasing food waste. Could composting more of our food waste help keep our landfills emptier? 1</p>
            </div>
        </a>
    </div>
    <div class="project">
        <a href="project2-details.html" target="">
            <img src="project2-image.jpg" alt="Project 2">
            <div class="caption">
                <h3>Project 2</h3>
                <p>Short description of Project 2</p>
            </div>
        </a>
    </div>
</section>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Email me at <a href="mailto:bridgethartung.bh@gmail.com">bridgethartung.bh@gmail.com</a></p>
    </section>
    <footer>
        <p>© 2025 Bridget Hartung.</p>
    </footer>
</body>
</html>
