# TORCS Lab Results

## What I Changed
Changed `TARGET_SPEED` from 100 to 150 in `torcs_jm_par.py`.

## What I Observed
At TARGET_SPEED = 100, the car drove smoothly and conservatively around Alpine 1, 
staying well within track limits. At TARGET_SPEED = 150, the car drove significantly 
faster on straights but struggled more in tight corners, occasionally drifting toward 
the barriers. The increased speed made the steering corrections more aggressive.

## One Thing That Surprised Me
How sensitive the car behavior is to a single parameter change. Increasing speed by 50% 
didn't just make the car faster it changed the entire driving character, making it 
more erratic and harder to control in corners.

## One Thing I Would Try Next
I would reduce BRAKE_THRESHOLD from 0.9 to 0.6 to make the car brake earlier before 
corners at the higher speed, which might allow it to maintain 150 km/h target speed 
while staying on track more consistently.