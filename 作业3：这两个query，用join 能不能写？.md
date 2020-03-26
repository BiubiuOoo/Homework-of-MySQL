## 作业3：这两个query，用join能不能写？
#### 1.两个query

```SQL
select * from t_employee2 WHERE sal > (
select sal from t_employee2 WHERE ename='SMITH');

select * from t_employee2 WHERE (sal, job) = (
select sal,job from t_employee2 where ename = 'smith');
```
#### 我感觉可以用join写出来，但是感觉比这个更复杂，研究了很久，没研究出来该怎么写，老师可以讲讲吗？：）
