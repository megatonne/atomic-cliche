# Atomic Cliché
A lightly flavored email pattern library

The purpose of this email framework is to provide usable base code to email developers who hand code and to incorporate the best practices and concepts which have not crossed over from front end web design.

The cliches used here are:
1. Normalize the base styles of a multitude of email clients. Some of this will be in the head for clients which respect it, some of this will be in the base inline styles for clients which sever the head.
2. Separate style from content ... where possible. Write minimal styles inline to represent a design in clients which sever the head.
3. Enhance the inheritance of clients to cascade from the greatest parent possible in the most begrudging clients. 
4. Atomic Design: the framework will be segmented into atoms, molecules, and organisms which can live in a environment (layout) to form a ecology of patterns which represent the vast majority of needs.
5. Use minimal helper classes, named clearly, which are reused extensively and modified by a organism level class chain.
