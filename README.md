# SIR

The rules of using the said program. Please use this structure only.

>>? every mango is a fruit
>> I understand
>>? alphonso is a mango
>> I understand
>>? Is alphonso a fruit
>> Yes


--debug 
run this command to see the adding and searching of the relationships

>>? debug
>>? every mango is a fruit
  adding fact   adding fact   I understand
>>? alphonso is a mango
  adding fact   adding fact   I understand
>>? is alphonso a fruit
  path -  alphonso  to  fruit
    path -  mango  to  fruit
>>  Yes e*ms* ['ms']

--dump
shows the relationships
>>? dump
  mango      : s : fruit
  fruit      : S : mango
  alphonso   : m : mango
  mango      : M : alphonso
