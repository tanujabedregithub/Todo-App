import React, { useState } from 'react';

const Todo = ({ id, text, completed }) => {
 return (
    <div className={completed ? 'todo-completed' : ''}>
      {text}
    </div>
 );
};

const TodoList = ({ todos })
