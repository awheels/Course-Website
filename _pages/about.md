---
layout: inner
title: About
permalink: /about/
---

<!-- Start First Tabs-->
<div id="tabbed-nav">
    <!-- Tab Navigation Menu -->
    <ul>
        <li><a>General</a></li>
        <li><a>Late Policy</a></li>
        <li><a>Test Retake Policy</a></li>
    </ul>
    <!-- Content container -->
    <div>
        <div>
            <p>Coming soon!</p>
        </div>
        <div>
            <h4>Late Policy</h4>
            <table class="table table-responsive table-bordered">
              <thead>
                <tr>
                  <th class="col-xs-2">Days Late</th>
                  <th class="col-xs-10">Consequences</th>
                </tr>
              </thead>
              <tbody>
                <tr class="bg-success">
                  <th scope="row">0-1</th>
                  <td>Consequences</td>
                </tr>
                <tr>
                  <th scope="row">2-5</th>
                  <td>Consequences</td>
                </tr>
                <tr>
                  <th scope="row">6-7</th>
                  <td>Consequences</td>
                </tr>
                <tr class="bg-danger">
                  <th scope="row">>7</th>
                  <td>Consequences</td>
                </tr>
              </tbody>
            </table>
        </div>
        <div>
            <h4>Retake Policy</h4>
            <p>Coming soon!</p>
        </div>
    </div>
</div>

<script>
    jQuery(document).ready(function ($) {
        /* jQuery activation and setting options for the first tabs*/
        $("#tabbed-nav").zozoTabs({
            rounded: false,
            multiline: true,
            style: "clean",
            theme: "flat-alizarin",
            size: "medium",
            spaced: true,
            responsive: true,
            animation: {
                effects: "slideH",
                easing: "easeInOutCirc",
                type: "jquery"
            },
            defaultTab: "tab1"
        });
    });
</script>
