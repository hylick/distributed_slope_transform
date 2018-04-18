FROM gcr.io/kubeflow-images-staging/tensorflow-1.6.0-notebook-cpu
USER root
RUN pip install pyqt5
COPY --chown=jovyan:root gen_data.py /home/jovyan/gen_data.py
COPY --chown=jovyan:root model.py /home/jovyan/model.py
COPY --chown=jovyan:root run.py /home/jovyan/run.py
USER jovyan
