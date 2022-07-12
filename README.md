# -No-show-appointments
> **:This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row**.

‘ScheduledDay’ tells us on what day the patient set up their appointment.
‘Neighborhood’ indicates the location of the hospital.
‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

<a id='Quest'></a>

## Questions



### Question(s) for Analysis


>****: Clearly state one or more questions that we plan on exploring over the course of the report. we will address these questions in the **data analysis**
>****: Once we start coding, Pandas Series, and DataFrames where appropriate rather than Python lists and dictionaries. Also, ** use good coding practices**, such as, define and use functions to avoid repetitive code. We'll se appropriate comments within the code cells, explanation in the mark-down cells, and meaningful variable names. 

>**: As we mentioned, our main goal is to find out the main reason that drives patients to attend or not to attend, and we will look into the matter through eight axes**.

>: 1- age

>: 2- sex

>: 3- Get scholarships

>: 4- Get a text message

>: 5- Diabetes

>: 6- Hypertension disease

>: 7- Alcohol addiction

>: 8- Residential location


## Conclusions

finally, The data show that the presence of female patients is more than that of men with a noticeable difference
Also, the percentage of attendance from customers who did not receive messages is more than from those who received them

something else we need to takecare of is Jardim Camburi region most of our visitors came form there.

There are four levels of handcap.  Although Most patients have the first level of handcap, but this is not a big deal, life may contain some inconveniences, especially for patients .

After repeating the experience of messages again, the content can be judged, because it is the first time to send messages


It is also recommended to add some medical services for women and children, in order to take advantage of the percentage of the number of patients!
### Limitations
**most of the patients are female but there is no clear correlation between gender , age , hypertension , shcolarship , diabetes , alcoholism , handcap , sms_received and showing.**
