// ==UserScript==
// @name         WHOWHERE 57575757
// @namespace    http://tampermonkey.net/
// @version      3.0
// @description  WhoWhere  created by 5̴7̴5̴7̴5̴7̴5̴7̴   from GARTIC IO
// @author       5̴7̴5̴7̴5̴7̴5̴7̴
// @author       5̴7̴5̴7̴5̴7̴5̴7̴
// @match        *://gartic.io/*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=gartic.io
// @grant        none
// @downloadURL https://update.greasyfork.org/scripts/499209/WHOWHERE%2057575757.user.js
// @updateURL https://update.greasyfork.org/scripts/499209/WHOWHERE%2057575757.meta.js
// ==/UserScript==

(function() {
    'use strict';

    // Sayfa yüklendiğinde betiği çalıştır
    console.log('Gartic.io WhoWhere hazirdir!');

    // HTML yapısını ekleyelim
    const overlay = document.createElement('div');
    overlay.className = 'overlay';

    const header = document.createElement('header');
    header.innerHTML = '<h2>WhoWhere  by  5̴7̴5̴7̴5̴7̴5̴7̴  </h2>';
    overlay.append(header);

    const p = document.c
