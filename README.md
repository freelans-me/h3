задание 1
import logging

logging.basicConfig(filename='sims.log', level=logging.DEBUG, format='%(asctime)s:%(levelname)s:%(message)s')

class SimsSimulation:
    def __init__(self):
        # симооляция
    
    def simulate(self):
        # симоляция
        for i in range(10):
            logging.debug('Step {}'.format(i))
            задание 2
            import time

def timeit(func):
    def wrapper(*args, **kwargs):
        start_time = time.time()
        result = func(*args, **kwargs)
        end_time = time.time()
        print('Час виконання функції {}: {} секунд'.format(func.__name__, end_time - start_time))
        return result
    return wrapper

@timeit
def my_function():
