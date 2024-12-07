Admin Dashboard - Role-Based Access Control (RBAC)
This project implements a React-based Admin Dashboard with role-based access:

Features: 
Admin:

Manage users and creators.
Assign or toggle roles (user/creator).
Add new members.
Creator:

Create, edit, and manage posts using a rich text editor.
View post history.
User:

View posts.
Follow/unfollow creators.
Shared:

Protected Routes: Role-based page access.
Optimized UI: Shimmer loading, debounce inputs.
Responsive Design: Mobile-friendly sidebar.
Technologies:
React, React Router, Context API, Reducer.
Tailwind CSS, TinyMCE (rich text editor).
Project Structure:
Components: Forms, navbars, shimmer loader.
Context: Auth and Blog state management.
Pages: Dashboards, writing, post history, unauthorized access.
