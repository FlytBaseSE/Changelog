# Improvements to Go To Location (GTL) : Task Altitude

## Introduction

We’re excited to introduce Task Altitude—a powerful addition to the Go To Location feature that brings smarter, safer navigation to your autonomous flights. This parameter lets operators define a dedicated cruising height between takeoff and destination, simplifying altitude planning and improving obstacle clearance in complex environments. Whether you're flying over varied terrain, near infrastructure, or operating BVLOS, Task Altitude adds a new layer of confidence and control to your drone missions.

<figure><img src="../.gitbook/assets/Image 27-05-25 at 3.10 PM.jpeg" alt=""><figcaption><p>Task Altitude Setting during Go To Location (GTL)</p></figcaption></figure>

## Key Features

* Maximum Altitude Priority: The drone will always ascend to the highest of Safe Takeoff Altitude or Task Altitude before horizontal travel.
* Task Altitude settings only affect flight paths when the drone would otherwise descend below the threshold.
* Mid-mission changes to Task Altitude apply only to subsequent navigation commands, maintaining route stability.

<figure><img src="../.gitbook/assets/Image 27-05-25 at 3.30 PM.jpeg" alt=""><figcaption><p>Behavior of Task Altitude Settings</p></figcaption></figure>

## Benefits

* Enhanced Safety: Maintain safe clearance from obstacles and terrain throughout missions.
* Greater Control: Define precise flight paths when navigating complex environments.
* Reduced Risk: Avoid tall structures by setting appropriate cruising altitudes.

## Configuring Task Altitude:&#x20;

* Task Altitude can be set in the Go To Location (GTL) configuration window (alongside Safe Takeoff Altitude and Waypoint Altitude).
* Additionally it can also be defined in the Device Settings page for configuring default values that persist across flights.
