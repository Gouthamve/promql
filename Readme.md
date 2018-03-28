# PromQL

This is a fork of the `prometheus/promql` package that allows `.` in metric names. Right now this is a complete fork of the package but the plan is to just have the new parser here and vendor most of the promql package.


This will allow people to implement PromQL against datasources that have `.` in the metric names.
