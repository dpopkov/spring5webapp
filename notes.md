Notes on the project
====================

3 - Add Publisher
-----------------
1. Add Publisher entity.
2. Establish one-to-many relationship: `@OneToMany, @ManyToOne, @JoinColumn`.
3. Add PublisherRepository.
4. Add data initialization in BootstrapData.

2 - Repositories
----------------
1. Add repository interfaces for entities: `EntityRepository extends CrudRepository<ValueType, IdType>`. 
2. Add class BootstrapData which implements org.springframework.boot.CommandLineRunner

1 - JPA Entities
----------------
1. Add entities Author and Book.
2. Establish many-to-many relationship: `@ManyToMany, @JoinTable, @JoinColumn`.
3. Add equals/hashCode methods (by id field).

0 - GitHub Workflow
-------------------

1) Fork repo to your account
2) Check out your fork to your local work space: `git clone <url>`
3) start with the master branch and follow along the coding exercises in the course
4) If you have problems then you can make comparisons with branches: 
    `RightClick -> Git -> Compare with Branch`
5) Add remote repo:
```
git remote add sfgRepo https://github.com/springframeworkguru/spring5webapp.git
git fetch
```
