---
layout: post
title: Select row in GnomeDbRawGrid
date: 2008-09-30 02:49:55.000000000 +08:00
type: post
published: true
status: publish
categories:
- gtk
tags:
- gtk
- select row
- treeview
meta:
  _edit_last: '5225680'
author:
  login: paragasu
  email: paragasu@gmail.com
---

GnomeDbRawGrid come from GtkTreeView widget.
So we can select row using gtk_tree_view_selection_select_iter() and get the current selected row gtk_tree_view_get_selection().

    GnomeDbRawGrid *grid;
    GtkTreeView *tree_view;
    tree_view = GTK_TREE_VIEW (grid);


Related  
[Gnome db raw grid](http://svn.gnome.org/viewvc/libgnomedb/trunk/libgnomedb/gnome-db-raw-grid.c?view=markup)
