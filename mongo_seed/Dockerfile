# Copyright (c) Microsoft Corporation and others. Licensed under the MIT license.
# SPDX-License-Identifier: MIT

FROM mongo:5.0.6
RUN mkdir /definitions
COPY ./definitions/* definitions/
COPY ./curations/* curations/
COPY ./seed_data.sh seed_data.sh
CMD sh seed_data.sh
