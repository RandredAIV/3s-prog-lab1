# RU
# Абстрактные структуры данных

## Описание
Реализация набора абстрактных структур данных на C++ с поддержкой
сохранения и загрузки данных из файлов.

## Реализованные структуры
- Динамический массив — добавление, вставка по индексу, удаление, замена, получение элемента
- Односвязный список — добавление в начало/конец, удаление, поиск элемента
- Двусвязный список — двунаправленный обход, добавление и удаление с обоих концов
- Стек — операции push/pop/peek на основе связного списка
- Хеш-таблица — хранение пар ключ-значение с разрешением коллизий
- Полное бинарное дерево — вставка, удаление, поиск узлов

Все структуры поддерживают чтение и запись данных из/в файл.

## Структура файлов
├── Array.h                # Динамический массив (шаблонный класс)  
├── LinkedList.h           # Односвязный список (шаблонный класс)  
├── DoubleLinkedList.h     # Двусвязный список (шаблонный класс)  
├── Stack.h                # Стек (шаблонный класс)  
├── HashTable.h            # Хеш-таблица (заголовочный файл)  
├── HashTable.cpp          # Хеш-таблица (реализация)  
├── CompleteBinaryTree.h   # Полное бинарное дерево  
└── main.cpp               # Точка входа программы  

## Язык программирования
C++

## Запуск
Открыть терминал в VS Code и выполнить:

g++ *.cpp -o main
./main  

---

# EN
# Abstract Data Structures

## Description
Implementation of a set of abstract data structures in C++ with support
for saving and loading data from files.

## Implemented Structures
- Dynamic Array — push, insert by index, delete, replace, get element
- Singly Linked List — push front/back, delete, search
- Doubly Linked List — bidirectional traversal, push and delete from both ends
- Stack — push/pop/peek operations based on a linked list
- Hash Table — key-value storage with collision resolution
- Complete Binary Tree — insert, delete, search nodes

All structures support reading and writing data from/to a file.

## File Structure
├── Array.h                # Dynamic array (template class)  
├── LinkedList.h           # Singly linked list (template class)  
├── DoubleLinkedList.h     # Doubly linked list (template class)  
├── Stack.h                # Stack (template class)  
├── HashTable.h            # Hash table (header file)  
├── HashTable.cpp          # Hash table (implementation)  
├── CompleteBinaryTree.h   # Complete binary tree  
└── main.cpp               # Program entry point  

## Language
C++

## How to Run
Open terminal in VS Code and execute:

g++ *.cpp -o main
./main
