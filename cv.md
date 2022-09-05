# Palina Hramuzava
43a-198 Miroshnichenko st., Minsk, Belarus 220131  
palinahramuzava@gmail.com  
Cell:+375 44 7100768
### Objective:
to build accessible, high-performance webpages using innovative web strategies and standarts.


### Summary:
*	Experience working in HTML5, CSS3, JS, SQL, PHP.
*	Strong understanding of UI, cross-browser compatibility, general web functions and standarts.
*	Proactive communicator who can collaborate with other team-members to ensure successful completion of shared tasks.

### Code example
    window.addEventListener("load", function () {

		//// аккордеон ////

	var accord = document.querySelectorAll("#accord")[0];
    accord.sl = null; 
    accord.addEventListener("click", funAccV, false);

    function funAccV(e) {

	var kont = e.currentTarget;

	if (kont.sl &&  
		e.target !== kont) 
		TweenLite.to(kont.sl, 0.3, {
			css : {
				width : "70px",
				
			}
		});
	else if (e.target === kont) return;


	if (kont === e.target.parentNode) 
		kont.sl = e.target;
	else if (kont === e.target.parentNode.parentNode)
		kont.sl = e.target.parentNode;
	else
		return; 

	var toSlide = kont.sl.style.width !== "500px" ? 500 : 70;

	TweenLite.to(kont.sl, 0.3, { 
		css : {
			width : toSlide + "px",
			
		}
	});
	TweenLite.to(kont, 0.3, {
		css : {
			left:"170px",
			
		    }
	    });

    }

### Experiance:

*Custumer Care Expert*, A100 development, Minsk, 2019-2022

*Freelance web developer*, based in Minsk, (volunteering), 2017-2019
*	Code and modify websites, from layout to function and according to a client`s specifications.
*	Integrate data from various back-end services and databases
*	Analyzes tasks, provides work estimates, and manages own time to keep development on shedule
*	Negotiate with clients for appearing their requirements

*Custumer Care Expert*, Telecom Austria Group (Velcom), Minsk, 2013-2017
*	work with  customers to develop a solution to their problem
*	deal with difficult people
*	take the team leaders role in managing conflict

*Marketer*, Институт "Кадры Индустрии", Minsk, 2011-2013
*	Support a comprehensive customer engagement model through development and implementation of integrated multichannel campaigns.
*	Develop annual budget required to support tactical plan and manage Multichannel marketing budget.

### Education:
*	AS in web-developing, BSUIR, Minsk, 2017
*	BS in ecology, ISEU, Minsk, 2013

### English
*   [StreamLine Language School English test result](https://test.str.by): Intermediate (CEFR B1)
*   I’m trying to up my English level every day, I use applications in smartphone: Duolingo and Chutterbugstream     
  