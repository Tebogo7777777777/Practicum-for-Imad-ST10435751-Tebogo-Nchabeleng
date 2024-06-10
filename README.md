# Practicum-for-Imad-ST10435751-Tebogo-Nchabeleng
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/3YPsmhN4)
Tebogo Nchabeleng 

ST10435751 

Pseudocode for imad 

0.Start  

1. Declaration 

  string strMainScreenButton 

  string strExitButton  

                 string strTemparatureApp 

                 string strNextScreen 

                 string strDay[6]= “Monday”, “Tuesday”, “Wednesday”, “Thursday”, “Friday”, 			                 “Saturday”, “Sunday” 

                  num intTempMin[6]= 12,9,0,3,8,10// array for the minimum temperature 

                num intTemp Max[6]= 25,29,30,38,40 // array for the maximum temperature 

	   string strWeatherCondition[6] = “Sunny”, “Sunny”, “Overcast”, “Cold”, “Cold”,               						   “Cold”   

               String strName 

               String strStudentNumber 

               Num intAverage  

               String strClearButton 

               IntTotalTemp 

               StrUserChoice 

               IntMaxTemparatureIndex 

               IntMinTemparatureIndex 

                

 

     

 

 

 

 

*Splash Screen** 

 

    2 . output " Temperature App"// This is the Name for the app 

    3.  output"Please enter your name”// prompts the user to insert their name  

    4.  intput strName 

    5.  output “ Please enter your Student Number” 

    6. input  strStudentNumber  

     8 . output"Main Screen” 

     9 . output " Exit" 

    10.                  While condition=True 

                              if userChoice = strMainScreenButton then 

                              output MainScreen() 

                              else if userChoice = strExitButton then 

                                    exit 

                                          else 

                                          output "incorrect choice. Please try again." 

                                        end If 

                                 end if 

                        end While 

          

                   

   

        **Main Screen** 

          MainScreen() 

 

   11     While condition=True 

                       output "Enter the day you would like to see the weather for" 

                 For i = 0 TO 6 

                      Input strDay[i] 

                end for 

                           If userChoice = strDetailedViewScreen Then 

                                     Move To DetailedViewScreen(screenTimeArray) 

                            End If  

                                    If userChoice = strClearButton 

                                                         clear screenTimeArray 

                                       output "Data cleared. Please enter the day you would like to see the     				temparature." 

                                       end  If userChoice = strExit Then 

                                             exit app 

                           else 

                                    output "Incorrect choice . Please try again." 

                              end If 

             end While 

12.   intTotalTemparature=0 

         For intcount=0 to 6 step 1 

                   IntTotalTemparature=intTotalTemparature+intTemp[intCount] 

        end for 

13. intAverage=intTotalTemparature/7 

14 .output “ The average temparature is “+ IntAverage 

       

 

 

 

**Detailed View Screen** 

        15.  output "Detailed View Screen:" 

           for intCount = 0 to 4 Step 1  

                       If    intTemp[intCount] > intMaxTemp then 

                                        intMaxTemp = intTemp[intCount] 

                                               intMaxTempIndex = intCount  

                       endif 

                                                                If intTemp[intCount] < intLowTemp then 

                                                             IntMinTemp = intTemp[intCount] 

                                                    IntMinTempIndex = intCount  

                                                Endif 

              Endfor  

 16.    output "The highest recorded temperature is " + intMaxTemp +  

                          " on " + strDay+ “strWeatherCondition”+[intMaxTempIndex] 

 17. output "The lowest recorded temperature is " + intLowTemp +  

                      " on " + strDay + strWeatherCondition +[intLowTempIndex] 

 

 

  18 .  Output “Main Screen Button” 

  19.         Output  “Exit " 

 

 20 .        IF userChoice = strMainScreenButton Then 

                 Move To MainScreen() 

                End if 

 21.       IF userChoice = strExit Then 

                       exit 

             End if 

22.        output "Incorrect choice. Please try again." 

23.      stop

Purpose of the app
The Purpose of this app is to show the user The minimum and maximum temperature ,The average temperature of day and how hot or cold the day will be The temperature app is solving a knowledge problem and informing the user what to expect on a day to day basis. The target Audience for this app is young people in university or college.This app has three screen which allows the user to insert their Name and surname and student number.The app also allows the user to insert a specific day and it will then show the user the minimum and the maximum temperature of that specific day in the week.The app is user friendly with bright colours to attract the users attention. 
    
![image](https://github.com/VCPTA/haw1-imad5112-practicum-submission-Tebogo7777777777/assets/164181125/a165f5f7-a135-4bbb-ab69-1de6cabc2185)
![image](https://github.com/Tebogo7777777777/Practicum-for-Imad-ST10435751-Tebogo-Nchabeleng/assets/164181125/8bbaa956-67b8-40ad-8a9e-47a2067da065)
![image](https://github.com/Tebogo7777777777/Practicum-for-Imad-ST10435751-Tebogo-Nchabeleng/assets/164181125/c58ee392-7e2f-4900-8648-8ae5368cd555)




