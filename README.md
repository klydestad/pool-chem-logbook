The purpose of this application is to act as a tool and logbook for balancing the chemistry of a public pool. Given a set of measurements for alkalinity, chlorine content, and pH, the application will provide several useful functions. Readings can be added for specific pools at certain times, and saved to a previously loaded logbook. Given a set range, it can determine whether a measurement is out of range, and if so how much it is. When it is out of range, a pop-up alert will occur. It also logs all readings to a logbook, allowing easy access for previous data. Additionally, it allows the user to view all the readings recorded, as well as filtering to see the current readings, to get a better history of the pool. For ease of use, it also enables filtering by pool type. All of these functions culminate in a useful digital pool logbook.

FUTURE ADJUSTMENTS(not in scope of project): things could be added such as a calculator to determine exactly how much of a chemical needs to be added to fix the pool chemistry, and a statistical summary report can be requested, ideally with several filters such as only certain chemical types and a range of days/single date.

This project is of interest to me because I work as a lifeguard, and noticed that any time a measurement is out of range, the person adding them has to find a piece of paper and go down a certain chemical chart to find how much of a certain corrective chemical to use. This is rather inefficient. Also, all of our measurements are recorded in a weekly notebook, which makes it difficult to track trends over time. This has lead to unexpected closures of certain pools for emergency maintenance in the past, so the need for such an application seems apparent to me. I hope that by implementing this project, I can design one for my workplace and propose it as a tool for my coworkers and I to use in replacement of traditional methods.





https://github.com/user-attachments/assets/55a8e370-75de-43fc-94ce-bc6d145ba289





User Stories


As a user, I want to be able to add a chemical reading with different chemical parameters, so that I can monitor the water quality.
As a user, I want to choose which pool the new reading is for, so I can add a pool reading to a specific pool.
As a user, I want all new readings added to be added to a list of past pool readings for the specific pool, and to view these lists.
As a user, I want to be able to simultaneously view the current readings of all pools of interest.
As a user, I want to have the option to save each separate pool history list to file.
As a user, I want to be able to be able to load each separate pool history list from file (if I so choose), so that I may continue adding to each pool's chemical history.
As a user, I want to be alerted if any of the data for chemical levels that I record is out of range, and be reminded what the range is.


Instructions for User


You can generate the first required action related to adding Xs to a Y by clicking the "Add New Pool Reading" Button Panel. Specify the pool type as one of: hottub, shallowpool, lanepool
You can generate the second required action related to adding Xs to a Y by clicking the "Filter Readings By Pool" Button Panel, specify pool type as one of: hottub, shallowpool, lanepool, and can do again after adding/loading an arbitrary amount of pool readings.
You can locate my visual component by clicking the "Add New Pool Reading" Button Panel, completing a reading, then clicking any button. A graphic indicating the reading has been added appears and disappears with the instantiation of a new button.
You can save the state of my application by clicking the "Save Pool Logbook" Button Panel.
You can reload the state of my application by clicking the "Load Pool Logbook" Button Panel.
