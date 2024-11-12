---
title: "BugBounty Profile"
layout: archive
permalink: /bugbounty/
author_profile: false
sidebar:
  nav: "bugbounty"
header:
  overlay_filter: 0.5  
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <link rel="canonical" href="{{ site.url }}{{ page.url }}">
  <style>
    body {
      background-color: #181b20; /* Background color of the body */
      font-family: Arial, sans-serif;
      color: #fff; /* Text color */
    }

    /* Styling the Recent Posts Section */
    .recent-posts {
      margin-top: 20px;
      padding: 20px;
      background-color: #2a2f36; /* Dark background for the recent posts box */
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    /* Styling for the heading of Recent Posts */
    .recent-posts h2 {
      font-size: 24px;
      color: #4CAF50; /* Green color for the title */
      margin-bottom: 15px;
    }

    /* Styling the links inside Recent Posts */
    .recent-posts a {
      color: #4CAF50; /* Green color for the links */
      text-decoration: none;
      font-weight: bold;
      font-size: 18px;
      display: block;
      margin: 10px 0;
    }

    /* Hover effect for links */
    .recent-posts a:hover {
      text-decoration: underline;
    }

    /* Styling for the Bug Table */
    .bug-table {
      margin-top: 30px;
      padding: 20px;
      background-color: #2a2f36; /* Background for the bug table */
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    .bug-table table {
      width: 100%;
      border-collapse: collapse;
    }

    .bug-table th, .bug-table td {
      padding: 12px;
      text-align: left;
      border-bottom: 1px solid #555; /* Light border between rows */
    }

    .bug-table th {
      background-color: #444; /* Dark background for table headers */
      color: #fff;
    }

    .bug-table td {
      background-color: #333; /* Slightly lighter background for table rows */
      color: #fff;
    }

    /* Optional style for overall page structure */
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }
  </style>
</head>
<body>

  <!-- Main content container -->
  <div class="container">
    
    <h1>Welcome to My BugBounty Profile</h1>
    <p>Explore my recent activities and blog posts about bug bounties and web security!</p>
    
    <!-- Recent Posts Section -->
    <div class="recent-posts">
      <h2>Recent Posts</h2>
      <ul>
        <li><a href="https://medium.com/@adhamelhansye/the-power-of-github-recon-c279809551ee?source=user_profile_page---------0-------------15d9384b8fa5---------------" target="_blank">The Power of Github Recon</a></li>
        <li><a href="https://medium.com/@adhamelhansye/information-disclosure-leads-to-ftp-server-takeover-536d1929bcfa?source=user_profile_page---------1-------------15d9384b8fa5---------------" target="_blank">FTP Server Takeover</a></li>
        <li><a href="https://medium.com/@adhamelhansye/weak-registeration-implementation-leads-to-pre-account-takeover-3740bc4c6958?source=user_profile_page---------2-------------15d9384b8fa5---------------" target="_blank">Pre Account Takeover</a></li>
        <li><a href="https://medium.com/@adhamelhansye/how-i-find-7x-subdomain-takeover-in-one-program-106fea7543b5?source=user_profile_page---------3-------------15d9384b8fa5---------------" target="_blank">7x Subdomain Takeover</a></li>
      </ul>
    </div>

    <!-- Bug Table Section -->
    <div class="bug-table">
      <h2>Bug Tracker</h2>
      <table>
        <thead>
          <tr>
            <th>Bug Number</th>
            <th>Bug Name</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>30x</td>
            <td>Reflected Cross Site Scripting </td>
          </tr>
          <tr>
            <td>4x</td>
            <td>Pre Account Takeover</td>
          </tr>
          <tr>
            <td>25x</td>
            <td>Leaks Credentails leads to ATO</td>
          </tr>
          <tr>
            <td>1x</td>
            <td>Information disclosure leads to FTP Server Takeover</td>
          </tr>
          <tr>
            <td>7x</td>
            <td>Subdomain Takeover</td>
          </tr>
          <tr>
            <td>2x</td>
            <td>ClickJacking</td>
          </tr>
          <tr>
            <td>3x</td>
            <td>Logic Bugs</td>
          </tr>
        </tbody>
      </table>
    </div>

  </div>

</body>
</html>
