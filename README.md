# logger
Python A logging module based on the logging library

Based on Python 3.12

usage:

from logger import setup_logging, logger



setup_logging(service_name="DataService", level="INFO")



logger.info("Test")

logger.debug("Test")

logger.warning("Test")

logger.exception("Test")

logger.error("Test")

logger.critical("Test")