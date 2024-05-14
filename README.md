# startup-tools
Various tools that are useful if you're running a startup company, such as tools for analyzing revenue or stock options. Check out the notebooks folder for Jupyter notebooks I have found useful in running MailChannels.

## Notebooks

### Stock Option Price Calculator

This notebook allows you to calculate the number of stock options you should grant an employee in order for them to enjoy a given net present value benefit from having the options. The notebook implements a Monte Carlo simulation to ascertain the net present value of an option grant with a given distribution of share price growth scenarios. We then use a binary search to find the number of options that, given the same distribution, would deliver a desired net present value.

If you're wondering how many options to give employees, this calculator at least can give you a reasonable idea of what upside the employees will get, based on some numerical analysis rather than guesswork. I find this method superior to "rules of thumb" such as allocating a certain percentage of the company to certain employees.
