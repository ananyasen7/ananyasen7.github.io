---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Research Assistant
          company: Desearch Research Institute Reno
          company_url: 'https://www.dri.edu/'
          company_logo: dri
          location: Reno, Nevada
          date_start: '2024-01-01'
          date_end: ''
          description: Working on differentiating Cyclogenesis with and without Large Amplitude Mesoscale Gravity Waves.
        - title: PhD
          company: University of Nevada Reno
          company_url: 'https://www.unr.edu/'
          company_logo: unr
          location: Reno, Nevada
          date_start: '2024-01-01'
          date_end: ''
          description: Working on differentiating Cyclogenesis with and without Large Amplitude Mesoscale Gravity Waves.
        - title: Project Associate
          company: IIT Kanpur
          company_url: 'https://www.iitk.ac.in/'
          company_logo: iitk
          location: Kanpur
          date_start: '2023-06-01'
          date_end: '2023-12-01'
          description: Ambient Air Quality Monitoring using Indigenous Technology (AMRIT) project for Centre of Excellence, ATMAN (Advanced Technologies for Monitoring Air-quality indicators) under the supervision of Prof. Sachidanand Tripathi.
        - title: Master's Thesis
          company: IIT Bhubaneswar
          company_url: 'https://www.iitbbs.ac.in/'
          company_logo: iitbbs
          location: Bhubaneswar
          date_start: '2022-05-01'
          date_end: '2023-05-01'
          description: Air Quality and Stagnation over India - A Comprehensive Analysis under the supervision of Dr. V. Vinoj.
        - title: Masters of Science
          company: IIT Bhubaneswar
          company_url: 'https://www.iitbbs.ac.in/'
          company_logo: iitbbs
          location: Bhubaneswar
          date_start: '2021-05-01'
          date_end: '2023-05-01'
          description: Atmosphere and Ocean Sciences, 9.61 CGPA (Batch Topper).
        - title: Bachelor of Science
          company: University of Lucknow
          company_url: 'https://www.lkouniv.ac.in/'
          company_logo: uol
          location: Bhubaneswar
          date_start: '2018-05-01'
          date_end: '2021-05-01'
          description: Geology, Physics and Mathematics.

    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2024-10-07'
          description: UNR Graduate Dean’s Merit Scholarship recipient for the 2024-25 academic year in recognition of academic excellence and scholarly potential.
          organization: UNR
          organization_url: 
          title: UNR
          url: 'https://www.unr.edu/nevada-today/read-watch-listen/recognitions/10072024-graduate-deans-merit-scholarship-winners'
        - certificate_url: 
          date_end: ''
          date_start: '2022-05-01'
          description: Qualified UGC-CSIR NET/JRF - AIR 19th for Earth, Atmosphere & Planetry Sciences category (for Lectureship & Junior Research Fellow).
          organization: UGC NET
          organization_url: 
          title: UGC-CSIR NET/JRF
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-05-01'
          description: Qualified Joint Admission Test for Masters (JAM) - AIR 131 for Geology.
          organization: JAM
          organization_url: 
          title: JAM
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2019-05-01'
          description: Intercollege science model presentation PHYSOC 360, University of Lucknow - Winner, Brownfield project on smart city.
          organization: University of Lucknow
          organization_url: 
          title: PHYSOC 360
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2018-05-01'
          description: Study Hall Educational Foundation, Lucknow - Winner, Poetry Recitation 'Yuva March'.
          organization: Study Hall Educational Foundation
          organization_url: 
          title: Yuva March
          url: ''
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
      text:
    design:
      columns: '2'
      view: citation
  - block: accomplishments
    id: initiatives
    content:
      title: Initiatives
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2023-09-01'
          description: 'Created a [python script](https://github.com/ananyasen7/cpcb-aqi) to fetch, aggregate, and export air quality data for specified cities and date ranges from CPCB using the given API and command-line arguments.'
          organization: Github
          organization_url: https://github.com/ananyasen7
          title: Air Quality Data Fetcher from CPCB
          url: 'https://github.com/ananyasen7/cpcb-aqi'
        - certificate_url: 
          date_end: ''
          date_start: '2023-04-01'
          description: 'I assisted in coordinatoin of on campus recruitment for graduating students.'
          organization: IIT-BBS
          organization_url: 
          title: Student Placement Coordinator, MSc Atmospheric and Ocean Sciences
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2022-05-01'
          description: Participant in webinar - NASA Applied Remote Sensing Training Program (ARSET).
          organization: NASA
          organization_url: 
          title: Accessing & Analyzing Air Quality Data from Geostationary Satellites
          url: 
        - certificate_url:
          date_end: ''
          date_start: '2018-07-01'
          description: Student Volunteer.
          organization: India International Science Festival
          organization_url:
          title: 'Science for Transformation'
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2021-06-01'
          description: 'Participant outreach program - Indian Institute of Remote Sensing.'
          organization: ISRO
          organization_url: 
          title: 'Geospatial technology for Hydrological Modelling'
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-08-01'
          description: 'Industrial Training - participant.'
          organization: IIT-M
          organization_url: 
          title: 'Short Range, Seasonal & Extended Range Forecast'
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-10-01'
          description: 'Industrial Training - participant.'
          organization: INCOIS
          organization_url: 
          title: 'Tsunami Forecast, Remote Sensing & GIS, Biogeochemistry of Ocean, Ocean Modelling & forecast'
          url: ''
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact Me
      subtitle:
      text: 
      email: ananyasen1607@gmail.com
      phone:
      contact_links:
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
