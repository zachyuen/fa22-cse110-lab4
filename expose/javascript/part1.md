1. values added: 20
2. final result: 20
3. values added: 20
4. The code returns an error because let has block scope and result was declared inside the if else block so it's only visible inside that block. Since line 13 is outside that block, there is no variable defined as result for line 13 to access.
5. The code returns an error due to line 7 which tries to resassign result which is a const variable which prevents it from being reassigned after the first time it's assigned.
6. The code returns an error because const has block scope so result is only accessible within the if else block it was defined in. Since line 13 is outside that block, it can't access result.
