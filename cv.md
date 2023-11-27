# **ANNA BEZUHLA**

## Contact information
Mail: <bezuglaya.am@gmail.com>  
Phone: +49 176 57843953

## About myself
As a frontend developer and former graphic designer, I have a unique blend of skills that allows me to create visually appealing and functional websites and applications. I am passionate about coding and am constantly seeking to improve my skills and stay up-to-date with the latest technologies. My background in graphic design has given me an eye for aesthetics and attention to detail that helps me create beautiful and effective user interfaces.

## Job experience

### Frontend Software Engineer (Part-time)
05/2022 – Present  
[Bits & Likes](https://www.bitsandlikes.de/)   
*Dortmund, Germany*  
* Creating different components from simple to complex (multi-level nesting / various animations)
* Decomposed and refactored existing components into smaller ones
* Integrating third-party tools and APIs into websites (like Google Analytics or Instagram)
* Troubleshooting and debugging issues with website functionality and user experience
* Conducting quality assurance and browser compatibility testing    
*Stack: JavaScript, HTML, CSS, Vue.js, Nuxt.js, three.js, Tailwind, Git, TYPO3, Adobe Creative Suite*

## Education

### Master Computer Science
09/2021 – 12/2022  
National University «Zaporizhzhia polytechnic»  
*Zaporizhzhia, Ukraine*  

### Bachelor Computer Science
09/2017 – 06/2021  
National University «Zaporizhzhia Polytechnic  
*Zaporizhzhia, Ukraine*

## Skills

**Skills**: 
* Adobe Creative Suite
* Java, JavaScript
* Git
* Blender    

**Languages**:
* English - B2
* Russian - Native
* Ukrainian - Native

## Code example
**Missing Number from Leetcode:** Given an array nums containing n distinct numbers in the range [0, n], return the only number in the range that is missing from the array

    function missingNumber(nums: number[]): number {
    let fullArray = [];
    for(let i=0; i < nums.length; i++){
        fullArray[nums[i]] =-1;
    }
     for(let i=0; i < fullArray.length + 1; i++){
         if(fullArray[i] != -1){
             return i;
         }
     }
    };
