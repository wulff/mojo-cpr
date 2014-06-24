CPR of the day
==============

This Mojo app creates a list of all possible CPR numbers (with check digits) for the current date.

Read more about CPR numbers (in Danish):

* https://cpr.dk/cpr-systemet/opbygning-af-cpr-nummeret/
* https://cpr.dk/media/167692/personnummeret%20i%20cpr.pdf


Installation
------------

Clone this repository and create a `cpr.conf` file with the following content:

    {
        'secret' => 'my-app-secret',
        'listen' => 3000,
    };
