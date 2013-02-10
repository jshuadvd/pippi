Quite alpha!

Install with pip:
    
    pip install pippi

Take a look at the generator scripts in orc/ for some examples of usage. [Docs coming...]

Or, with the optional (linux-only - requires ALSA) interactive console:

    pip install pippi[realtime]

The pippi console:

    pippi

    Pippi Console
    pippi: dr o:2 wf:impulse n:d.a.e t:30s h:1.2.3

Starts the pippi console and generates a 30 second long stack of impulse trains on D, A, and E each with partials 1, 2, and 3.

Take a look at the scripts in orc/ for more arguments and generators.