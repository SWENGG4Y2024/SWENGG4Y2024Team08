# Software Requirement Specification
 
## Table of Contents
-  [1. Introduction](#1-introduction)
   - [1.1 Purpose](#11-purpose)
   - [1.2 Intended Audience](#12-intended-audience)
   - [1.3 Intended Use](#13-intended-use)
   - [1.4 Scope](#14-scope)
   - [1.5 Definitions, Acronyms and Abbreviations](#15-definitions-acronyms-and-abbreviations)
- [2. Overall Description](#2-overall-description)
   -  [2.1 Product Perspective](#21-product-perspective)
   -  [2.2 Product Features](#22-product-features)
   -  [2.3 User Classes and Characteristics](#23-user-classes-and-characteristics)
   -  [2.4 Operating Environment](#24-operating-environment)
   -  [2.5 Design and Implementation Constraints](#25-design-and-implementation-constraints)
   -  [2.6 User Documentation](#26-user-documentation)
   -  [2.7 Assumptions & Dependencies](#27-assumptions-&-dependencies)
-  [3. System Features](#3-system-features)
   -  [3.1 Admin Features](#31-admin-features)
   -  [3.2 User Features](#32-user-features)
   -  [3.2 Content Creator Features](#33-trainer-features)
- [4. Functional Requirements](#4-Functional-Requirements)
   -  [4.1 User Interface Requirements](#41-user-interface-requirements)
   -  [4.2 Hardware Interface Requirements](#42-hardware-interface-requirements)
   -  [4.3 Software Interface Requirements](#43-software-interface-requirements)
   -  [4.4 Communication Interface Requirements](#44-communication-interface-requirements)
-  [5. Non Functional Requirements](#5-non-functional-requirements)
   -  [5.1 Performance Requirements](#51-performance-requirements)
   -  [5.2 Safety Requirements](#52-safety-requirements)
   -  [5.3 Security Requirements](#53-security-requirements)
   -  [5.4 Software Quality Attributes](#54-software-quality-attributes)
 
## 1. Introduction
 
   - ### **1.1 Purpose**
        The purpose of this document is to provide a comprehensive overview of the requirements for the development of "Galaxy TV+," a streaming service responsive in approximately 3 seconds for the viewers offered by Galaxy Inc. This document serves as a reference for stakeholders involved in the development process and outlines the functional and non-functional requirements of the system.

   - ### **1.2 Intended Audience**
     The intended audience for Galaxy TV+ includes stakeholders such as developers, designers, project managers, and 
 quality assurance teams involved in the development and deployment of the streaming service. Additionally, this document 
 is relevant for executives, investors, and other decision-makers responsible for overseeing the project's progress and 
 ensuring alignment with business goals.
       
  - ### **1.3 Intended Use**
     Galaxy TV+ is intended to provide users with access to a diverse library of exclusive movies, TV shows, 
     documentaries, and original content produced or acquired by Galaxy Inc. Users can subscribe to the service to stream 
     content on various devices, including devices such as iPhone, iPad and Android smartphones.
   - ### **1.4 Scope**
        The scope of this product includes the development of a robust database and an intuitive interface to facilitate 
 easy user interaction. Users will be able to subscribe to various plans offered by the service, granting them access to a 
 wide range of exclusive movies, TV shows, documentaries, and more. Subscribers will have the flexibility to choose a plan 
 that best suits their preferences and viewing habits, enabling them to enjoy uninterrupted streaming of premium content. 
 Additionally, the service will provide features such as personalized recommendations, watchlist management, and offline 
 viewing capabilities to enhance the overall potential user/subcribers experience.
 
   - ### **1.5 Definitions, Acronyms, and Abbreviations**
        Conventions        | Definition
        -----------        | -----------
        Subscription       | An arrangement where potential subscriber pay a fee in advance to access the content and features offered by Galaxy TV+, typically on a recurring basis.
        Rating             | A classification or ranking based on a comparative assessment of their quality, standard, or performance, often used to categorize and recommend content to subscribers based on their preferences.
        Account            | An identity associated with the Galaxy TV+ service, typically created by Subscribers through registration or sign-up processes. subcribers can manage their account settings, preferences, and subscription details through their Galaxy ID.
        Categories         | Classification of different types of content available on the Galaxy TV+ platform, organizing movies, TV shows, and other media into distinct genres or themes to facilitate browsing and discovery.
        Offline Mode       | A feature that allows users to download select content from Galaxy TV+ for offline viewing, enabling them to enjoy movies and TV shows without an internet connection, often used for convenience during travel or limited connectivity situations.
        Download           | The process of transferring data from the Galaxy TV+ platform to a subscribers device for offline viewing, typically involving the storage of media files locally on the device.
        Subscribe          | The action of signing up for a subscription plan offered by Galaxy TV+, granting subscribers access to exclusive content and features in exchange for a recurring fee paid in advance.
 
##  **2. Overall Description**
 
   - ### **2.1 Product Perspective**
        Galaxy TV+ is positioned as a premium streaming service offering exclusive content produced or
        acquired by Galaxy Inc. The service aims to compete with other streaming platforms by providing a
        curated selection of high-quality movies, TV shows, and documentaries, available for streaming on
        various devices.
 
 
   -  ### **2.2 Product Features**
      - Content Library: Galaxy TV+ offers a diverse collection of exclusive movies, TV shows,
      documentaries, and original content produced or acquired by Galaxy Inc.
      - Personalized Recommendations: The service uses algorithms to provide personalized
      recommendations to users based on their viewing history, preferences, and ratings.
      - Multiple Profiles: subscribers can create multiple profiles under one account, allowing for
      personalized viewing history, recommendations, and watchlists for each Viwer.
      - Offline Viewing: Galaxy TV+ allows Viwers to download selected content for offline viewing,
      enabling them to watch movies and TV shows without an internet connection.
      - Continuous Playback: The service automatically plays the next episode of a TV series,
      facilitating binge-watching sessions for Viwers.
      - Parental Controls: Galaxy TV+ offers parental controls to restrict access to age-inappropriate
      content and create child-friendly profiles. Content should be restricted and based on age ratings (G, PG, PG-13, R, etc.
      - Search and Filtering: Viwers can search for specific titles, actors, or genres, and filter content
      based on criteria such as release year and ratings.
      - Cross-Platform Access: Galaxy TV+ is accessible on various devices, including iPhone, iPad
      and Android smartphones, ensuring seamless streaming across different platforms.
 
   -  ### 2.3 **Subscriber Classes and Characteristics**
      - Subscribers: viewers who subscribe to Galaxy TV+ to access the content and features
      offered by the service.
      - Content Creators: Individuals or companies responsible for creating the content available on
      Galaxy TV+, including movies, TV shows, documentaries, and original programming.
      - Content Providers: Companies that license content to Galaxy TV+ for streaming on the
      platform, such as movie studios, TV networks, and production companies.
 
        **characteristics of these subscriber classes could include:**
          - Subscribers: They may have different levels of technical expertise, but all expect an easy-to-use and reliable streaming service that offers a broad range of high-quality content.
          - Content Creators: They may have specific technical requirements for video and audio
          quality, as well as a desire to protect their intellectual property rights and control how
          their content is distributed.
          - Content Providers: They may have specific contractual requirements and business goals
          related to licensing their content to Galaxy TV+, such as maximizing revenue and protecting
          their brand image.
          
 
   -  ### **2.4 Operating Environment**
        - Galaxy TV+ supports a wide range of devices, including:
          - Apple Devices: Compatible with iPhone, iPad running iOS 13 or
        later, iPadOS 13 or later.
          - Android Devices: Android 5.0 or later.
    
   -  ### **2.5 Design and Implementation Constraints**
        These are the limitations and guidelines that need to be considered during the development of Galaxy
        TV+. Some of the design and implementation constraints are:
        - Platform Compatibility: Ensure compatibility with iOS and Android platforms, following Galaxy's design guidelines.
        - Data Security: Prioritize user privacy and security, complying with Galaxy's privacy policies
        and GDPR.
        - Server Capacity Management: Manage server capacity and network traffic for optimal
        performance and scalability to accommodate a large number of concurrent Viwers
        - Privacy Protection: The service must adhere to privacy regulations and data protection
        standards to safeguard user data and ensure compliance with legal requirements.
        - User Interface Consistency: Maintain a consistent and intuitive interface following Galaxy's
        Human Interface Guidelines.
        - API Integration: Integrate with Galaxy services and third-party APIs, adhering to privacy and
        security guidelines.
        - Localization: Support multiple languages and regions, complying with regional content
        regulations.
        - Content Compliance: Adhere to Galaxy's content guidelines and implement parental controls.
 
 
   -  ### **2.6 User Documentation**
        User documentation for Galaxy TV+ includes a range of materials that are designed to help users
        understand how to use and get the most out of their application. Some of them are as
        follows:
        - Getting Started Guide: An introductory guide on how to access and navigate the Galaxy TV+
        app on various devices.
        - Account Setup: Instructions for creating or signing in to an Galaxy ID and subscribing to Galaxy
        TV+.
        - Troubleshooting: Common issues and solutions for technical problems, such as playback
        errors or account issues.
        - Privacy and Security: Guidelines on how Galaxy protects user privacy and security while using
        Galaxy TV+.
        - Help Desk: Our chatbot is available 24/7 to provide you with instant support. For complex issues that require human intervention, our live chat and email support are available during business hours.
 
   -  ### **2.7 Assumptions & Dependencies**
        **Assumptions:**
        - Users of Galaxy TV+ will have reliable internet access to stream content online.
        - Users will access Galaxy TV+ on compatible devices, such as iPhone, iPad and Android smartphones.
        - Users will need to create an account and sign in to access Galaxy TV+ content, with
        appropriate authentication mechanisms in place.
        - Galaxy TV+ will have the necessary licenses and agreements in place to make content
        available for streaming in target regions.
        - Galaxy TV+ will have secure payment processing mechanisms in place for users to subscribe
        to the service and make payments for subscription fees.
        - Content on Galaxy TV+ will be properly categorized and tagged for easy search and discovery
        by users.
        - Content on Galaxy TV+ will meet certain quality standards, including resolution, audio quality,
        and subtitle availability, to ensure a satisfactory user experience.
        Dependencies:
        - Galaxy TV+ may depend on third-party APIs for secure payment processing and efficient
        content delivery.
        - Galaxy TV+ may depend on content licensing agreements with studios, production
        companies, and other content providers to legally stream their content on the platform.
        - Galaxy TV+ may be subject to regional regulations and compliance requirements, such as
        content censorship laws, which may impact the availability of certain content in specific regions.
        - Galaxy TV+ may depend on reliable and scalable technology infrastructure, including servers,
        databases, and networking components, to support its streaming service and handle the large
        volume of user requests
        - Galaxy TV+ may depend on users' devices to meet certain technical requirements, such as
        screen size, resolution, and audio capabilities, to ensure an optimal viewing experience.
        - Galaxy TV+ may depend on reliable internet service providers to ensure that users have
        sufficient bandwidth and network stability to stream content seamlessly
 
## 3. System Features
 
   - ### **3.1 Admin Features**
      The features available to the Admin include:
      1. Add, delete, or update content such as movies, TV shows, and categories.
      2. Manage user accounts and subscriptions.
      3. View transaction details and manage membership packages.
      4. Monitor and manage feedback and ratings provided by users.
      5. Validate and verify content based on guidelines and standards.
   - ### **3.2 User Features**
        The features available to the users (members) are:
      1. View profile details and subscription status.
      2. Browse and search for movies and TV shows.
      3. Watch trailers and previews for upcoming content.
      4. Add movies and TV shows to watchlists or favorites.
      5. Rate and review content and provide feedback.
   - ### **3.3 Content Creator Features**
      The features available to content creators (producers, directors, etc.) include:
      1. Upload and publish original content, such as movies and TV shows.
      2. Manage metadata and promotional materials for their content.
      3. Monitor performance metrics, such as views and ratings.
      4. Engage with users through comments and discussions.
      5. Receive analytics and insights on audience engagement and preferences.
         
## 4. Functional Requirements
 
   - ### **4.1 User Interface Requirements**
 
      - **Home Page:** The home page of the Galaxy TV+ app shall feature curated collections of
        recommended movies and TV shows based on the user's preferences and viewing history. It
        shall include a prominent search bar for users to easily find specific content.
      - **Content Details Page:** Each movie or TV show's details page shall present essential
        information such as title, poster, synopsis, rating, and cast. Additionally, it shall suggest
        related content to the user.
      - **Watchlist:** Users shall have the ability to add movies and TV shows to their watchlist directly
        from the content details page. The watchlist shall be accessible from the user's profile
        section, showcasing all saved content.
      - **Playback Controls:** The app shall provide intuitive playback controls, including play, pause,
        stop, rewind, and fast-forward. Additionally, it shall feature a volume slider and a full-screen
        mode for an immersive viewing experience.
      - **Subscription Plans:** Users shall be able to explore and select from various subscription plans
        offered by Galaxy TV+, each presenting its benefits and pricing details.
 
 
   -  ### **4.2 Hardware Interface Requirements**
 
      - **Display:** Galaxy TV+ shall support video playback on a range of devices like
        smartphones, tablets optimizing the viewing experience for different display
        sizes and resolutions.
      - **Audio:** The service shall support stereo and surround sound audio playback, adapting to the
        capabilities of the user's device. It shall also ensure compatibility with various audio codecs
        for seamless audio playback.
      - **Network:** Galaxy TV+ shall require an internet connection with a minimum bandwidth of 5
        Mbps for standard definition (SD) playback and 25 Mbps for high definition (HD) playback. It
        shall support Wi-Fi and cellular data networks for flexible accessibility.
      - **Storage:** The app shall not rely on local storage for content playback, streaming all movies
        and TV shows directly from Galaxy's servers. However, users may have the option to
        download content for offline viewing, requiring sufficient storage capacity on their device.
     
   -  ### **4.3 Software Interface Requirements**
     
      - **Operating System:** Galaxy TV+ shall support major operating systems, including iOS, iPadOS and
        Android ensuring compatibility with all supported devices. It shall provide system
        requirements for optimal performance on each supported platform.
      - **Content Delivery** Network (CDN): Galaxy TV+ shall utilize a robust Content Delivery Network
        (CDN) to ensure fast and reliable content delivery to users worldwide, optimizing streaming
        performance.
      - **Payment Gateway:** The app shall integrate with a secure payment gateway to process
        subscription payments and transactions. It shall support various payment methods, including
        credit cards, Paytm and other online payment systems.
 
   -  ### **4.4 Communication Interface Requirements**
 
      - **API:** Galaxy TV+ shall offer an API (Application Programming Interface) for third-party
        developers to integrate its service into their applications, providing access to its content
        catalog and user data.
      - **Social Media Integration:** The app shall seamlessly integrate with popular social media
        platforms like Facebook, Twitter, and Instagram, enabling users to share their favourite
        content with friends and followers.
      - **Customer Support:** Galaxy TV+ shall provide comprehensive customer support through
        multiple channels, including email, phone, and live chat. It shall also offer an extensive FAQ
        section and community forums for user assistance.
      - **Content Providers:** Galaxy TV+ shall establish partnerships and licensing agreements with
        content providers, including renowned studios and production companies, ensuring a diverse
        and high-quality content library. Compliance with copyright laws and proper content
        licensing shall be maintained at all times.
 
## **5. Non Functional Requirements**
 
   -  ### **5.1 Performance Requirements**
 
      - **Response Time:** The system should respond to user requests in less than 1 second for most
        operations, such as searching for a movie or starting a video playback.
      - **Playback Quality:** Video content should be delivered in high quality, with minimal buffering
        or stuttering, even under adverse network conditions. The video quality should be optimized
        according to the user's device and network bandwidth.
      - **Scalability:** The system should be able to handle a large number of concurrent users,
        particularly during peak hours, without experiencing any significant slowdown or crashes.
        The system should be able to scale up or down dynamically based on the user load.
      - **Availability:** The system should be available to users 24/7, with a minimum uptime of 99.9%.
        Any scheduled maintenance or downtime should be communicated to users in advance.
      - **Security:** The system should protect user data and prevent unauthorized access to the
        platform. The system should be able to detect and prevent security threats, such as DDoS
        attacks, SQL injection attacks, and cross-site scripting attacks.
      - **Reliability:** The system should be reliable, with a low probability of errors or system crashes.
        The system should have mechanisms to recover from errors and prevent data loss.
      - **Responsiveness:** The system should be responsive to user actions, such as fast-forwarding or
        pausing a video. The system should be able to detect and respond to these actions quickly
        and accurately.
      - **Compliance:** The system should comply with industry standards and regulations, such as the
        Digital Millennium Copyright Act (DMCA) and the General Data Protection Regulation
        (GDPR).
 
   -  ### **5.2 Safety Requirements**
 
      - **User Safety:** The system should ensure the safety of users while using the service. It should
        have clear guidelines for appropriate content, detect and prevent cyberbullying and
        harassment, and filter inappropriate content effectively.
      - **Content Safety:** The system should ensure that the provided content is safe and free from
        malicious elements such as malware, viruses, or spyware. It should also prevent copyright
        infringement, piracy, and illegal content.
      - **Platform Safety:** The system should ensure the safety of the platform itself, detecting and
        preventing unauthorized access, tampering, and security breaches, while maintaining high
        availability and avoiding system crashes.
      - **Data Safety:** The system should protect user data from unauthorized access, tampering, and
        theft, and prevent data loss, corruption, or damage through appropriate measures.
      - **Emergency Procedures:** The system should have emergency procedures to handle
        unforeseen events like natural disasters, power outages, or system failures, minimizing their
        impact on the service and ensuring quick recovery.
      - **Compliance:** The system should comply with relevant safety regulations and standards, such
        as Occupational Safety and Health Administration (OSHA) standards and National Fire
        Protection Association (NFPA) codes.
 
   -  ### **5.3 Security Requirements**
       
      - **Access Control:** The system should provide proper access control mechanisms to ensure only
        authorized personnel have access to sensitive data and functionalities, using user
        authentication and authorization mechanisms.
      - **Secure Communication:** The system should use secure communication protocols such as
        HTTPS and SSL/TLS to ensure confidentiality and integrity of data transmission, encrypting
        sensitive data before transmission.
      - **Data Protection:** The system should protect user data from unauthorized access and prevent
        data loss, corruption, or theft through appropriate data backup and recovery mechanisms.
      - **Auditing and Monitoring:** The system should maintain logs of user activities and system
        events to detect and prevent security breaches, with real-time monitoring to respond to
        security threats effectively.
      - **Compliance:** The system should comply with industry standards and regulations such as
        General Data Protection Regulation (GDPR) and Payment Card Industry Data Security
        Standard (PCI DSS).
      - **Vulnerability Management:** The system should have a comprehensive vulnerability
        management program, including security assessments, threat modeling, and penetration
        testing, addressing identified vulnerabilities promptly.
      - **Incident Response:** The system should have an incident response plan to respond to security
        incidents like data breaches and system compromises effectively, with defined roles,
        communication procedures, and escalation paths.
 
   -  ### **5.4 Software Quality Attributes**
 
      - **User Safety:** Ensure user safety by providing clear guidelines for appropriate content and
        effective filtering of inappropriate content.
      - **Content Safety:** Ensure the safety of provided content by preventing malware, viruses, piracy,
        and illegal content.
      - **Platform Safety:** Ensure the safety of the platform by detecting and preventing unauthorized
        access and security breaches.
      - **Data Safety:** Ensure user data safety through protection against unauthorized access,
        tampering, and loss.
      - **Emergency Procedures:** Implement emergency procedures to minimize the impact of
        unforeseen events on the service.
      - **Compliance:** Ensure compliance with relevant safety regulations and standards.
