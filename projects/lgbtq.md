---
layout: project
type: project
image: img/lgbtq/logoblack.jpg
title: "UHM LGBTQ+ Website Redesign"
date: 2023
published: true
labels:
  - React
  - Bootstrap 5
  - Webpack
  - GitHub
  - Vercel
summary: "A responsive web application for LGBTQ+ Center for the University of Hawai'i at Manoa"
---

<div class="text-center p-4">
  <img src="../img/lgbtq/lgbtq-web.png" class="img-thumbnail" >
</div>

A team of friends and I took on the redesign of UH Manoa's LGBTQ+ Center's web application as our first project for our club, 8bit. The revamped website features a modern and accessible design that prioritizes ease of navigation and content engagement.

This website is a frontend application that utilizes React.js framework for its hooks and reusable components and Bootstrap 5 for its responsiveness and grid system. ensuring the website's adaptability across different devices. To efficiently manage dependencies, optimize assets, and facilitate modularization, we integrated Webpack into our development workflow. This decision was rooted in the desire to improve code maintainability and simplify the deployment process.

Here is some code that illustrates how our application displays the information:

```
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossOrigin="anonymous" referrerPolicy="no-referrer"></link>
            <footer className="text-center text-lg-start text-white bg-dark">
                <section className="d-flex justify-content-between p-4" style={{backgroundColor: '#2C4230'}}>
                
                    <div className="me-5">
                        <span>Get connected with us on our social networks:</span>
                    </div>

                    <div>
                        <a href="https://www.instagram.com/uhmlgbtqcenter/" target="_blank" className="text-white me-4">
                            <i className="fab fa-instagram"></i>
                        </a>
                    </div>

                </section>

                <section className="">
                    <div className="container text-center text-md-start mt-5">
                        <div className="row mt-3">

                            <div className="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
                                <h6 className="text-uppercase fw-bold">Newsletter</h6>
                                <hr className="mb-2 mt-0 d-inline-block mx-auto" style={{width: 60, height: 2, backgroundColor: '#7c4dff'}}/>
                                <p>
                                    Want to know what we're up to? Sign up for the newsletter!
                                </p>
                                <form className="form">
                                    <div className="form-group">
                                        <input type="email" className="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email" style={{}}/>
                                    </div>
                                    <br />
                                    <button type="submit" className="btn text-white" style={{backgroundColor:"#2C4230", borderRadius: 100}}>Submit</button>
                                </form>
                            </div>

                            <div className="col-md-4 col-lg-3 col-xl-3 mx-auto mb-4">
                                <h6 className="text-uppercase fw-bold">Address</h6>
                                <hr className="mb-2 mt-0 d-inline-block mx-auto" style={{width:60, height:2, backgroundColor:"#7c4dff"}} />
                                <p><i className="fa fa-home mr-3"></i> U</p>
                                <p></p>
                                <p></p>
                            </div>

                            <div className="col-md-3 col-lg-2 col-xl-2 mx-auto mb-md-0 mb-4">
                                <h6 className="text-uppercase fw-bold">Contact</h6>
                                <hr className="mb-2 mt-0 d-inline-block mx-auto" style={{width: 60, height: 2, backgroundColor: '#7c4dff'}} />
                                <p><i className="fa fa-envelope mr-3"></i> 1234@hawaii.edu</p>
                                <p><i className="fa fa-phone mr-3"></i> + 1 (123) 456-7890</p>
                            </div>

                        </div>
                    </div>
                </section>
                <div className="text-center p-3" style={{backgroundColor: '#2C4230'}}>
                    ©2018-{new Date().getFullYear().toString().slice(-2)} University of Hawai&#699;i · Page last modified: January 14, 2024 
                </div>
            </footer>
  }
```
We are continuing to reconstruct this website and in the future we plan to utilize Django, which is a fullstack framework, to bring on additional modules for the admin dashboard of the website.