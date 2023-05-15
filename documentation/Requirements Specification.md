# Requirements Specification
## General Description
This is an application for the Pomodoro Technique of time management. The Pomodoro technique is a time management method that involves breaking work into 25-minute intervals called "pomodoro", with short breaks in between each interval, and longer ones after so many pomodori. The idea is that this structure can help users stay focused and productive while avoiding burnout and fatigue.

The application should provide a timer that users can set to (the default) 25 minutes, along with a countdown clock that indicates when the current pomodoro is over. After each pomodoro, the application provides a short break period of around 5 minutes, during which the user can rest and recharge. Once the break is over, the user can start another pomodoro and repeat the cycle.

In addition to basic timer functionality, Pomodoro applications should offers additional features such as customizable intervals, the ability to track progress and productivity, and the option to customize the length of the break period, and notify the user when the pomodoro and break is over.

### Sequence
1. Decide on the task to be done
2. Set up the Pomodoro Timer
3. Work on the task
4. End work when the timer rings and take a short Break
5. If you did less than three pomodori go to step 2 and repeat
6. After three pomodori, the forth pomodoro consist in a focus time and a longer break. Once the longer break finishes return to step 2

## Terms and Definitions

- **Pomodoro**: The interval of work time, usually 25 minutes.
- **Focus time**: Time spent working in pomodoro.
- **Break**: The interval of time to relax and decompress, can be short or long.
- **Short Break**: The break between two focus times, takes 5 or 10 minutes
- **Long Break**: after a set, the user should take a longer break usually 20 to 30 minutes.
- **Set**: A set consists in four pomodori in sequence
- TODO: **TBD**: How many pomodori the uses made in this session
- **Session**: The work session of a task.
- **Report**: Report of user productivity
- **Productivity**: How many pomodori was made in a period of time, how much time spent in focus time, how much time spent in breaks, etc.
- **Session report**: What was the task of the session, how many pomodori was made in that session, how many time was spent in focus time, how many time was spent in break time.

# System Requirements
1. Pomodoro
    1. The system should have a countdown timer.
    2. The system should notify the user when the countdown timer reaches zero
    3. The system should change between Pomodoro timer and break timer.
    4. The system should change the break lenght after the last pomodoro of a set.
    5. The system should count how many pomodori was made in this session.
    6. The system should have a task field.
    7. The system should should be able to interrupt a pomodoro.
        1. The system should flag the interrupted pomodoro.
    8. The system should permit the user to start the pomodoro.
    9. The system should permit the user to start the break.
2. The system should be customizable.
    1. The system should permit the user to change the pomodoro lenght.
    2. The system should permit the user to change the break lenght.
    3. The system should permit the user to change the long break lenght.
    4. The system should permit the user to change how many pomodori is in a set.
    5. The system should permit the user to change if they would be notified when the timer reach zero.
    6. The system should permit the user to change the notification sound.
3. The system should generate reports.
    1. The system should generate a session report.
    2. The system should generate a week report.
    3. The system should generate a month report.
    4. The system should generate a customizable period report.
    5. The system should generate an all-time report.
    6. The system should generate a frequency report.