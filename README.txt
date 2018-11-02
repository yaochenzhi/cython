python36 setup.py build_ext --inplace
python36 testing.py

mkdir dir
mv example_cy.cpython-36m-x86_64-linux-gnu.so example_py.py testing.py dir/
mv example_cy.cpython-36m-x86_64-linux-gnu.so example_cy.so
python36 testing.py