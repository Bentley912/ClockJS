# ClockJS
Simple Clock with Vanilla JS

Working more on Vanilla JS. This time I was working with tweaking transitions and transforms. I created the clock face and hands and seperated them. 

The challenge here was to getthe time using JS ( const now = Date(); ) and then have the clock represent that time in physical transition of degrees. 

So it was a simple math equation, for example with seconds, there 60 seconds in a minute, so 60 parts. We took sthe current time/60 * 360. This would give us a degree. Then the second - hand would move the correct amount of degrees every second. 

We repeated that same process with all the hands. 

I learned about using console.log to check whethere a function was working or not. For instance, 

      const seconds = now.getSeconds;
        console.log(seconds);       
        
 This would console.log as the seconds changed. It is an easy way to see different parts oof your function working as you code them . 
 
 I also worked with querySelector for the DOM, transitions, and transitions-time-effects. 
