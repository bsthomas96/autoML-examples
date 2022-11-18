## Error for 2_DecisionTree


Traceback (most recent call last):
  File "c:\Users\briat\AppData\Local\Programs\Python\Python310\lib\site-packages\supervised\base_automl.py", line 1087, in _fit
    trained = self.train_model(params)
  File "c:\Users\briat\AppData\Local\Programs\Python\Python310\lib\site-packages\supervised\base_automl.py", line 372, in train_model
    mf.train(results_path, model_subpath)
  File "c:\Users\briat\AppData\Local\Programs\Python\Python310\lib\site-packages\supervised\model_framework.py", line 286, in train
    learner.save(p)
  File "c:\Users\briat\AppData\Local\Programs\Python\Python310\lib\site-packages\supervised\algorithms\sklearn.py", line 45, in save
    joblib.dump(self.model, model_file_path, compress=True)
  File "c:\Users\briat\AppData\Local\Programs\Python\Python310\lib\site-packages\joblib\numpy_pickle.py", line 548, in dump
    with _write_fileobject(filename, compress=(compress_method,
  File "c:\Users\briat\AppData\Local\Programs\Python\Python310\lib\site-packages\joblib\numpy_pickle_utils.py", line 202, in _write_fileobject
    return _buffered_write_file(file_instance)
  File "c:\Users\briat\AppData\Local\Programs\Python\Python310\lib\site-packages\joblib\numpy_pickle_utils.py", line 117, in _buffered_write_file
    return io.BufferedWriter(fobj, buffer_size=_IO_BUFFER_SIZE)
MemoryError


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

