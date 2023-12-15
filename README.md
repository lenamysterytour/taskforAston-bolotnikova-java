
<h4>Задание для Aston. </h4>

1) Коды для заданий 1,2,3 находятся в классе AlgorithmTests
2) Текстовое решение 4ого задания
<p>Данную скобочную последовательность [((())()(())]] нельзя назвать правильной, поскольку все склобки должны закрываться. В данном случае сразу видно, что квадратных скобок непраное количество.
</p><p>Для соблюдения правильности можно скопировать скобки в программу notedpad++ либо другой компилятор и перебрать скобки кликом,  отслеживая, у какой из них при клике не подсвечивается пара из-за ее отсутствия. В данном примере правильным было бы добавить квадратную скобку в начало и кругую закрывающуюся после первых трёх открывающихся.
<p>Таким образом последовательность бы приобрела правильный вид, а именно [[((()))()(())]]</p> 
<p>Также можно использовать код с применением stack, и циклы, которые перебирают скобки, будут добавлять открывающиеся и затем стирать их с верхушки стека, если они совпадают с соответственной зеркально отображенной закрывающейся скобкой. Если в конце стек равен нулю, то последовательность правильная.
</p>