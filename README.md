https://devinterview.io/dev/react-interview-questions


1.  How does React work?
<details>
<summary>Answer</summary>
React creates a virtual DOM. When state changes in a component it runs a diff algorithm, which identifies what has changed in the virtual DOM. The second part of the algorithm updates the browser's DOM with only the things that have changed. This process is called reconciliation.


</details>

---
2. What is Context?
<details>
<summary>Answer</summary>
Context provides a way to pass data through the component tree without having to pass props down manually at every level. For example, user authentication, locale preference, UI theme.

```js
const { Provider, Consumer } = React.createContext(defaultValue);

```
> Usually written in a seperate store file where the default value is an object with the initial state. The Provider is used to wrap the root component and the Consumer is used to wrap the component that needs access to the context.

</details>

---
3. 
<details>
<summary>Answer</summary>
The virtual dom is a memory representation of the Real DOM. The representation of a UI is kept in memory and synced with the “real” DOM by a library such as ReactDOM. This process is called reconciliation.


</details>

---
4. What are Props in React?
<details>
<summary>Answer</summary>
**Props** are inputs to a react Component. They are passed to components upon creation using a naming convention similar to HTML tag attributes. They are data passed down from parent component to child component




</details>

---
5. What is the use of refs?
<details>
<summary>Answer</summary>
A ref is used to return a reference to the element. They should be avoided in most cases but are useful when we need direct access to a DOM element or an instance of a component. They are created using `React.createRef()` and attached to a React element via the ref attribute. The ref is then accessible via the current property of the ref. Refs are commonly assigned to an instance property when a component is constructed so they can be referenced throughout the component.


</details>

---
6. What is JEST?
<details>
<summary>Answer</summary>
Jest is a Javascript unit testing framework.


</details>

---
7. What are the advantages of using React?
<details>
<summary>Answer</summary>



</details>

---
8. What is ReactJS?
<details>
<summary>Answer</summary>
ReactJS is an open-source frontend JavaScript library which is used for building user interfaces especifically for single page applications. It is used for handling view layer for web and mobile apps. 


</details>

---
9. 
<details>
<summary>Answer</summary>



</details>

---
10. 
<details>
<summary>Answer</summary>



</details>

---
11. 
<details>
<summary>Answer</summary>



</details>

---
12. 
<details>
<summary>Answer</summary>



</details>

---
13. 
<details>
<summary>Answer</summary>



</details>

---
14. 
<details>
<summary>Answer</summary>



</details>

---
15. 
<details>
<summary>Answer</summary>



</details>

---
16. 
<details>
<summary>Answer</summary>



</details>

---
17. 
<details>
<summary>Answer</summary>



</details>

---
18. 
<details>
<summary>Answer</summary>



</details>

---
19. 
<details>
<summary>Answer</summary>



</details>

---
20. 
<details>
<summary>Answer</summary>



</details>

---
21. 
<details>
<summary>Answer</summary>



</details>

---
22. 
<details>
<summary>Answer</summary>



</details>

---
23. 
<details>
<summary>Answer</summary>



</details>

---
24. 
<details>
<summary>Answer</summary>



</details>

---
25. 
<details>
<summary>Answer</summary>



</details>

---
26. 
<details>
<summary>Answer</summary>



</details>

---
27. 
<details>
<summary>Answer</summary>



</details>

---
28. 
<details>
<summary>Answer</summary>



</details>

---
29. 
<details>
<summary>Answer</summary>



</details>

---
30. 
<details>
<summary>Answer</summary>



</details>

---
31. 
<details>
<summary>Answer</summary>



</details>

---
32. 
<details>
<summary>Answer</summary>



</details>

---
33. 
<details>
<summary>Answer</summary>



</details>

---
34. 
<details>
<summary>Answer</summary>



</details>

---
35. 
<details>
<summary>Answer</summary>



</details>

---
36. 
<details>
<summary>Answer</summary>



</details>

---
37. 
<details>
<summary>Answer</summary>



</details>

---
38. 
<details>
<summary>Answer</summary>



</details>

---
39. 
<details>
<summary>Answer</summary>



</details>

---
40. 
<details>
<summary>Answer</summary>



</details>

---
41. 
<details>
<summary>Answer</summary>



</details>

---
42. 
<details>
<summary>Answer</summary>



</details>

---
43. 
<details>
<summary>Answer</summary>



</details>

---
44. 
<details>
<summary>Answer</summary>



</details>

---
45. 
<details>
<summary>Answer</summary>



</details>

---
46. 
<details>
<summary>Answer</summary>



</details>

---
47. 
<details>
<summary>Answer</summary>



</details>

---
48. 
<details>
<summary>Answer</summary>



</details>

---
49. 
<details>
<summary>Answer</summary>



</details>

---
50. 
<details>
<summary>Answer</summary>



</details>

---
51. 
<details>
<summary>Answer</summary>



</details>

---
52. 
<details>
<summary>Answer</summary>



</details>

---
53. 
<details>
<summary>Answer</summary>



</details>

---
54. 
<details>
<summary>Answer</summary>



</details>

---
55. 
<details>
<summary>Answer</summary>



</details>

---
56. 
<details>
<summary>Answer</summary>



</details>

---
57. 
<details>
<summary>Answer</summary>



</details>

---
58. 
<details>
<summary>Answer</summary>



</details>

---
59. 
<details>
<summary>Answer</summary>



</details>

---
60. 
<details>
<summary>Answer</summary>



</details>

---
61. 
<details>
<summary>Answer</summary>



</details>

---
62. 
<details>
<summary>Answer</summary>



</details>

---
63. 
<details>
<summary>Answer</summary>



</details>

---
64. 
<details>
<summary>Answer</summary>



</details>

---
65. 
<details>
<summary>Answer</summary>



</details>

---
66. 
<details>
<summary>Answer</summary>



</details>

---
67. 
<details>
<summary>Answer</summary>



</details>

---
68. 
<details>
<summary>Answer</summary>



</details>

---
69. 
<details>
<summary>Answer</summary>



</details>

---
70. 
<details>
<summary>Answer</summary>



</details>

---
71. 
<details>
<summary>Answer</summary>



</details>

---
72. 
<details>
<summary>Answer</summary>



</details>

---
73. 
<details>
<summary>Answer</summary>



</details>

---
74. 
<details>
<summary>Answer</summary>



</details>

---
75. 
<details>
<summary>Answer</summary>



</details>

---
76. 
<details>
<summary>Answer</summary>



</details>

---
77. 
<details>
<summary>Answer</summary>



</details>

---
78. 
<details>
<summary>Answer</summary>



</details>

---
79. 
<details>
<summary>Answer</summary>



</details>

---
80. 
<details>
<summary>Answer</summary>



</details>

---
81. 
<details>
<summary>Answer</summary>



</details>

---
82. 
<details>
<summary>Answer</summary>



</details>

---
83. 
<details>
<summary>Answer</summary>



</details>

---
84. 
<details>
<summary>Answer</summary>



</details>

---
85. 
<details>
<summary>Answer</summary>



</details>

---
86. 
<details>
<summary>Answer</summary>



</details>

---
87. 
<details>
<summary>Answer</summary>



</details>

---
88. 
<details>
<summary>Answer</summary>



</details>

---
89. 
<details>
<summary>Answer</summary>



</details>

---
90. 
<details>
<summary>Answer</summary>



</details>

---
91. 
<details>
<summary>Answer</summary>



</details>

---
92. 
<details>
<summary>Answer</summary>



</details>

---
93. 
<details>
<summary>Answer</summary>



</details>

---
94. 
<details>
<summary>Answer</summary>



</details>

---
95. 
<details>
<summary>Answer</summary>



</details>

---
96. 
<details>
<summary>Answer</summary>



</details>

---
97. 
<details>
<summary>Answer</summary>



</details>

---
98. 
<details>
<summary>Answer</summary>



</details>

---
99. 
<details>
<summary>Answer</summary>



</details>

---
100. 
<details>
<summary>Answer</summary>



</details>

---
101. 
<details>
<summary>Answer</summary>



</details>

---
102. 
<details>
<summary>Answer</summary>



</details>

---
103. 
<details>
<summary>Answer</summary>



</details>

---
104. 
<details>
<summary>Answer</summary>



</details>

---
105. 
<details>
<summary>Answer</summary>



</details>

---
106. 
<details>
<summary>Answer</summary>



</details>

---
107. 
<details>
<summary>Answer</summary>



</details>

---
108. 
<details>
<summary>Answer</summary>



</details>

---
109. 
<details>
<summary>Answer</summary>



</details>

---
110. 
<details>
<summary>Answer</summary>



</details>

---
111. 
<details>
<summary>Answer</summary>



</details>

---
112. 
<details>
<summary>Answer</summary>



</details>

---
113. 
<details>
<summary>Answer</summary>



</details>

---
114. 
<details>
<summary>Answer</summary>



</details>

---
115. 
<details>
<summary>Answer</summary>



</details>

---
116. 
<details>
<summary>Answer</summary>



</details>

---
117. 
<details>
<summary>Answer</summary>



</details>

---
118. 
<details>
<summary>Answer</summary>



</details>

---
119. 
<details>
<summary>Answer</summary>



</details>

---
120. 
<details>
<summary>Answer</summary>



</details>

---
121. 
<details>
<summary>Answer</summary>



</details>

---
122. 
<details>
<summary>Answer</summary>



</details>

---
123. 
<details>
<summary>Answer</summary>



</details>

---
124. 
<details>
<summary>Answer</summary>



</details>

---
125. 
<details>
<summary>Answer</summary>



</details>

---
126. 
<details>
<summary>Answer</summary>



</details>

---
127. 
<details>
<summary>Answer</summary>



</details>

---
128. 
<details>
<summary>Answer</summary>



</details>

---
129. 
<details>
<summary>Answer</summary>



</details>

---
130. 
<details>
<summary>Answer</summary>



</details>

---
131. 
<details>
<summary>Answer</summary>



</details>

---
132. 
<details>
<summary>Answer</summary>



</details>

---
133. 
<details>
<summary>Answer</summary>



</details>

---
134. 
<details>
<summary>Answer</summary>



</details>

---
135. 
<details>
<summary>Answer</summary>



</details>

---
136. 
<details>
<summary>Answer</summary>



</details>

---
137. 
<details>
<summary>Answer</summary>



</details>

---
138. 
<details>
<summary>Answer</summary>



</details>

---
139. 
<details>
<summary>Answer</summary>



</details>

---
140. 
<details>
<summary>Answer</summary>



</details>

---
141. 
<details>
<summary>Answer</summary>



</details>

---
142. 
<details>
<summary>Answer</summary>



</details>

---
143. 
<details>
<summary>Answer</summary>



</details>

---
144. 
<details>
<summary>Answer</summary>



</details>

---
145. 
<details>
<summary>Answer</summary>



</details>

---
146. 
<details>
<summary>Answer</summary>



</details>

---
147. 
<details>
<summary>Answer</summary>



</details>

---
148. 
<details>
<summary>Answer</summary>



</details>

---
149. 
<details>
<summary>Answer</summary>



</details>

---
150. 
<details>
<summary>Answer</summary>



</details>

---
151. 
<details>
<summary>Answer</summary>



</details>

---
152. 
<details>
<summary>Answer</summary>



</details>

---
153. 
<details>
<summary>Answer</summary>



</details>

---
154. 
<details>
<summary>Answer</summary>



</details>

---
155. 
<details>
<summary>Answer</summary>



</details>

---
156. 
<details>
<summary>Answer</summary>



</details>

---
157. 
<details>
<summary>Answer</summary>



</details>

---
158. 
<details>
<summary>Answer</summary>



</details>

---
159. 
<details>
<summary>Answer</summary>



</details>

---
160. 
<details>
<summary>Answer</summary>



</details>

---
161. 
<details>
<summary>Answer</summary>



</details>

