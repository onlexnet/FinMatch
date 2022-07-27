Simple connector to Binance market to allow observe stream of requested data

It does not cover:
- Loading missing data (gaps in data stream when the µservice is off)
- Removing duplication of data (in case when two µservice was reading and publishing the same data twice)

