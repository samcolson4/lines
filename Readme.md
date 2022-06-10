# A collection of scripts
Scripts may need to be made executable before running:

```
chmod +x <script_name>
```

In some instances, it is useful to put the script in your path:

```
cp <script_name> <$YOUR_PATH>
```

It can then be called directly, without reference to the script's location.

---

## newConTask
Builds a new [Concourse](https://github.com/concourse/concourse) task yaml & shell script inside a folder of the same name. Useful automation of what can be a repetitive task.

## macSetup
A useful script to set up a new mac. Homebrew does the work for you in terms of getting an Apple Silicon version of an app where it is available (tested on an M1 Pro, late 2021).

I will continue adding to this list over time.

## kalias
Copies commonly used ```kubectl``` shortcuts to your clipboard as aliases that can then be set. Born of out necessity for the KodeKloud CKA labs, which all require you to either write out ```kubectl <do x>``` every time, or write out aliases every time. Also useful for the CKA exam.

## qi
Quickly intercept a Concourse container, without needing to type out the whole command.

## cumulativeTime
Calculates the cumulative time taken for each step of a *thing* (e.g. pipeline run) when provided with a list of times in a specific format. See `example-input/times.txt` for formatting help.
