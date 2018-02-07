# Stocker
Nifty Sensex data:  [date, time of day,
opening price, closing price, high, low and fractional change
in price from the previous time step]

Stopping criterion:
increase as it is also observed that the error tends to
increase by small amount and then decrease again:
• The change in error from one iteration to the next
falls below a threshold that the user can set.
• The error value begins to increase. There is a
relaxation factor here as well that allows minimal 
increase as it is also observed that the error tends to
increase by small amount and then decrease again
• If the number of iterations (or epochs) goes beyond a
certain limit. In our case the limit is set to 200.
