---
title: "An awsome community of Research Data Scientists"
permalink: /
layout: default
---

// Set up the KavaDocs Topic Tree in the Left Sidebar
var tabItem = new MetroTabItem() {Name = "KavaDocsTree"};

// Create the tab content user control
KavaDocsTopicTreeTab = tabItem;
Tree = new TopicsTree();
tabItem.Content = Tree;

// Create an ImageSource for the icon (custom code here)
var icons = new AssociatedIcons();
var imgSource = icons.GetIconFromFile("t.kavadocs");  // image source

Model.Window.AddLeftSidebarPanelTabItem(tabItem,"Kava Docs",imgSource); 

# Intro

Starting the trial go of writing and hosting a website through github, this is a first  step towards our altimate goal of making an open source community of research data scientists.

# Step1: if you are new to Makdown 

Feel free to checkout this link if you are new to makrdonw: 
[GitHub's Markdwon Guide]{https://guides.github.com/features/mastering-markdown/}