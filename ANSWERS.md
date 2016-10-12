## Questions

1. What is the difference between new and create for a model?
new method creates an object instance and the create method additionally tries to save it to the database if it is possible.

2. What command combined with new will emulate the same behavior as create?
save emulates the same as create

3. What is the default integer column that exists on every table but we did NOT define?
ID.

4. What single line of ruby code can insert a cat with the name "Kira" in the database?
cat.create(:name=> ‘Kira‘)
5. How did you like this homework in comparison with the previous homeworks?
I think this week's workload is good, and it also incorporates the idea of database well.'