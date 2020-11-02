---
date: 2020-11-02 20:07:44
title: Apply

---
<form name="contact" method="POST" data-netlify="true">
  <div class="form-group">
    <label for="fullName">Full Name</label>
    <input type="text" class="form-control" id="fullName" placeholder="Enter name">
  </div>
  <div class="form-group">
    <label for="email">Email Address</label>
    <input type="email" class="form-control" id="email" placeholder="john@email.com">
  </div>
  <div class="form-group">
    <label for="phone">Phone Number</label>
    <input type="text" class="form-control" id="phone" aria-describedby="phoneMsg" placeholder="Phone Number">
    <small id="phoneMsg" class="form-text text-muted">We'll never share your phone number with anyone else.</small>
  </div>
  <div class="form-group">
    <label for="about">About yourself</label>
    <textarea class="form-control" id="about" rows="5" aria-describedby="aboutMsg"></textarea>
    <small id="aboutMsg" class="form-text text-muted">You could include: Current studies, employment or hobbies</small>    
  </div>
  <div class="form-group">
    <label for="experience">Experience</label>
    <textarea class="form-control" id="experience" rows="5" aria-describedby="experienceMsg"></textarea>
        <small id="experienceMsg" class="form-text text-muted">Doesn't have to be cyber related</small>   
  </div>
  <div class="form-group">
    <label for="qualifications">Qualifications</label>
    <textarea class="form-control" id="qualifications" rows="5"></textarea>  
  </div>
  <div class="form-group">
    <label for="achievements">Key Achievements</label>
    <textarea class="form-control" id="achievements" rows="5"></textarea>  
  </div>
  <div class="form-group">
    <label for="skills">Related Skills</label>
    <textarea class="form-control" id="skills" rows="5"></textarea>  
  </div>
  
  
  
  <div class="form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>