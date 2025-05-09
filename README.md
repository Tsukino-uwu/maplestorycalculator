# maplestorycalculator

To find the Accuracy needed for a specific hit rate:
Credit to Ayumilove
Accuracy = (1 + H) * (1.84 + 0.07 * D) * Avoid

(H = desired hit rate in decimal form, e.g. 0.25 for 25%)
(D = monster level - your level. If negative, make it 0.)
(Avoid = monster’s avoid stat)
Use this when planning how much Accuracy you need for a specific hit chance.



To find your hit rate from current Accuracy:
Hit Rate = Accuracy / ((1.84 + 0.07 * D) * Avoid) - 1

(D = monster level - your level. If negative, make it 0.)
(Avoid = monster’s avoid stat)
Use this when you already know your Accuracy and want to check your hit chance. 
