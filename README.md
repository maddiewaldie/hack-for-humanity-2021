# Re-Entry Hub

## About the Project

People released from prison face a lot of obstacles due to their conviction history and incarceration. One obstacle upon release is getting necessary identification. Identification is essential for almost everything, including housing, employment, banking, getting a motel/hotel room, getting public benefits, and receiving medical care. Yet, people are often released from prison without a photo ID and commonly no longer have access to their social security card and birth certificate. And the process for getting each of these documents is complicated.

This website aims to make previously incarcerated people's integration into society easier. Keep reading to find more about the site's capabilities!

## Tour the Site!

### The Black & White Design

Research has shown that, when people are released from prison, they are often overwhelmed by their sudden independence and the fast-pace of the outside world.
As a result, many subconsciously find ways to become re-incarcerated in order to regain access to the same structure. We aimed to make our website as simple and user-friendly as possible by using black and white fonts and a simplistic structure, so we could present our information in a way that didn't overwhelm our audience.

### Homepage

The homepage displays a welcome message to the viewer.

### ID Resources

The ID resources tab of our website provides a comprehensive guide on how to go about obtaining (or renewing) your IDs. From step by step instructions, to lists of required identification materials, to maps, this section of the website has it all!

### Job Search

As stated above, many former prisoners experience difficulty finding a job after release. During their time spent in prison, many lose work skills and are given little opportunity to gain useful work experience. Moreover, the availability of job-training programs in prison has declined in recent years.

The job search tab of our website is designed to help people who were formerly incarcerated find jobs. Upon entering their location, this tab allows the user to find resources in their area that can help with employment.

## Behind the Software

This website was implemented using HTML, CSS, and Javascript. The maps were created using the Google Maps Javascript API, and the Birth Certificates Search was created using Microsoft Azure (SQL database, Azure cognitive search).

### Challenges Encountered

#### Microsoft Azure

Before this event, the team had never used Microsoft Azure. So, they encountered some challenges with using the API endpoint from Azure cognitive search to display the database in the UI. They found that the source of the problem was figuring out how to parse through the JSON object that was being received from the endpoint, and ultimately got it working.

#### Google Maps

The team also had a lot of trouble generating a unique API Key for the Google Map. But, they troubleshooted it and were able to find a solution.

Finally, the team ran into a few issues with the format of the maps. At one point, all the data points on our maps were shifted left into the Pacific Ocean. They realized that the CSS file was shifting the data points to the left, and were able to quickly resolve the issue.

## Meet the Team!

Maddie Waldie, Neena Ekanathan, Kamya Krishnan, and Divya Syal are freshman Computer Science and Engineering majors at Santa Clara University. They completed this project as a part of "Hack for Humanity," an event designed to solve pressing social issues using creativity and code.
